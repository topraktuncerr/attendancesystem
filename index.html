import React, { useState, useEffect } from 'react';
import { Download, Users, Calendar, CheckCircle, XCircle, Clock, Lock, LogOut } from 'lucide-react';

export default function SecureAttendanceSystem() {
  const [userType, setUserType] = useState(null); // null, 'teacher', 'student'
  const [teacherPassword, setTeacherPassword] = useState('');
  const [loginStudentNumber, setLoginStudentNumber] = useState('');
  const [isLoggedIn, setIsLoggedIn] = useState(false);
  
  const [currentWeek, setCurrentWeek] = useState(1);
  const [courseName, setCourseName] = useState('');
  const [studentList, setStudentList] = useState([
    { name: 'İBRAHİM GÜLTEKİN', number: '18070003013', department: 'İNŞAAT MÜHENDİSLİĞİ' },
    { name: 'ELİF EMİNE GÜNAL', number: '19070001053', department: 'BİLGİSAYAR MÜHENDİSLİĞİ' },
    { name: 'ERK YANKI URAL', number: '19070008012', department: 'MAKİNE MÜHENDİSLİĞİ' },
    { name: 'ERCE ÖZKAN', number: '20070001057', department: 'BİLGİSAYAR MÜHENDİSLİĞİ' },
    { name: 'İPEK ATIŞ', number: '20070002048', department: 'ENDÜSTRİ MÜHENDİSLİĞİ' },
    { name: 'İDİL ECE CEVAHİR', number: '20070007004', department: 'ENERJİ SİSTEMLERİ MÜHENDİSLİĞİ' },
    { name: 'SUDE ONFİDAN', number: '20070008016', department: 'MAKİNE MÜHENDİSLİĞİ' },
    { name: 'ÖMER ARICA', number: '20070008017', department: 'MAKİNE MÜHENDİSLİĞİ' },
    { name: 'SELİM MERT KIRCAALİLİ', number: '20070008019', department: 'MAKİNE MÜHENDİSLİĞİ' },
    { name: 'BERİL DERAN GÜRBÜZ', number: '20070008029', department: 'MAKİNE MÜHENDİSLİĞİ' },
    { name: 'ALİ HAKTAN SIĞIN', number: '21070001004', department: 'BİLGİSAYAR MÜHENDİSLİĞİ' },
    { name: 'ARDA ALTUNHAN', number: '21070001051', department: 'BİLGİSAYAR MÜHENDİSLİĞİ' },
    { name: 'EKREM TEMEL', number: '21070001070', department: 'BİLGİSAYAR MÜHENDİSLİĞİ' },
    { name: 'NESRİN ŞENTÜRK', number: '21070002005', department: 'ENDÜSTRİ MÜHENDİSLİĞİ' },
    { name: 'BATUHAN ŞİŞMAN', number: '21070002025', department: 'ENDÜSTRİ MÜHENDİSLİĞİ' },
    { name: 'KIVANÇ EFE ERGÖNÜL', number: '21070005027', department: 'ELEKTRİK-ELEKTRONİK MÜHENDİSLİĞİ' },
    { name: 'OĞUZ KOYUCAN', number: '21070005030', department: 'ELEKTRİK-ELEKTRONİK MÜHENDİSLİĞİ' },
    { name: 'ZEYNEP ARSLANBUĞA', number: '21070005042', department: 'ELEKTRİK-ELEKTRONİK MÜHENDİSLİĞİ' },
    { name: 'BESTE TEKİN', number: '21070007001', department: 'ENERJİ SİSTEMLERİ MÜHENDİSLİĞİ' },
    { name: 'EKİN ALTUNKAYA', number: '21070007004', department: 'ENERJİ SİSTEMLERİ MÜHENDİSLİĞİ' },
    { name: 'EMRE ERİŞİR', number: '21070008009', department: 'MAKİNE MÜHENDİSLİĞİ' },
    { name: 'İSMAİL CAN BERK DEMİRKAN', number: '21070008014', department: 'MAKİNE MÜHENDİSLİĞİ' },
    { name: 'CAN GİRGİN', number: '21070008016', department: 'MAKİNE MÜHENDİSLİĞİ' },
    { name: 'KEREM EROĞLU', number: '21070008017', department: 'MAKİNE MÜHENDİSLİĞİ' },
    { name: 'ARMAĞAN SOYLU', number: '21070008027', department: 'MAKİNE MÜHENDİSLİĞİ' },
    { name: 'ALP SERKAN MERKİT', number: '21070008033', department: 'MAKİNE MÜHENDİSLİĞİ' },
    { name: 'ATAKAN DİNÇER', number: '21070008034', department: 'MAKİNE MÜHENDİSLİĞİ' },
    { name: 'DEMET BÜYÜKTAŞ', number: '21070008206', department: 'MAKİNE MÜHENDİSLİĞİ' },
    { name: 'GÜRKAN EROĞLU', number: '22070001041', department: 'BİLGİSAYAR MÜHENDİSLİĞİ' },
    { name: 'EMRE EFE YÜKSEL', number: '22070001055', department: 'BİLGİSAYAR MÜHENDİSLİĞİ' },
    { name: 'SÜLEYMAN BATU SARI', number: '22070002015', department: 'ENDÜSTRİ MÜHENDİSLİĞİ' },
    { name: 'KADİR EMRE GÜNEŞ', number: '22070002047', department: 'ENDÜSTRİ MÜHENDİSLİĞİ' },
    { name: 'TOPRAK TUNCER', number: '22070005040', department: 'ELEKTRİK-ELEKTRONİK MÜHENDİSLİĞİ' },
    { name: 'EMRE CAN HEKİMOĞLU', number: '22070005053', department: 'ELEKTRİK-ELEKTRONİK MÜHENDİSLİĞİ' },
    { name: 'ILGAR ŞENOL', number: '22070007014', department: 'ENERJİ SİSTEMLERİ MÜHENDİSLİĞİ' },
    { name: 'EDA NUR ÇALIŞKAN', number: '22070008017', department: 'MAKİNE MÜHENDİSLİĞİ' },
    { name: 'SAMİ BERK ŞAHİN', number: '22070008021', department: 'MAKİNE MÜHENDİSLİĞİ' },
    { name: 'DENİZ ÜNVER', number: '22070008026', department: 'MAKİNE MÜHENDİSLİĞİ' },
    { name: 'AYKAN KANLI', number: '22070008034', department: 'MAKİNE MÜHENDİSLİĞİ' },
    { name: 'DENİZ KARATEPE', number: '22070008043', department: 'MAKİNE MÜHENDİSLİĞİ' },
    { name: 'AYŞEGÜL KARINYARICI', number: '22070003022', department: 'İNŞAAT MÜHENDİSLİĞİ' },
    { name: 'AHMET ÖZGÜR KORKMAZ', number: '21070001046', department: 'BİLGİSAYAR MÜHENDİSLİĞİ' }
  ]);
  const [attendanceRecords, setAttendanceRecords] = useState({});
  const [studentName, setStudentName] = useState('');
  const [studentNumber, setStudentNumber] = useState('');
  const [sessionCode, setSessionCode] = useState('');
  const [currentSessionCode, setCurrentSessionCode] = useState('');
  const [isSessionActive, setIsSessionActive] = useState(false);
  const [sessionStartTime, setSessionStartTime] = useState(null);
  const [timeRemaining, setTimeRemaining] = useState(10);
  const [loggedInStudentNumber, setLoggedInStudentNumber] = useState('');

  // Öğretmen şifresi (gerçek uygulamada güvenli olmalı)
  const TEACHER_PASSWORD = 'ogretmen123';

  const generateSessionCode = () => {
    return Math.random().toString(36).substring(2, 8).toUpperCase();
  };

  // Her 10 saniyede bir kod değişimi
  useEffect(() => {
    let interval;
    if (isSessionActive) {
      interval = setInterval(() => {
        setTimeRemaining(prev => {
          if (prev <= 1) {
            setCurrentSessionCode(generateSessionCode());
            return 10;
          }
          return prev - 1;
        });
      }, 1000);
    }
    return () => clearInterval(interval);
  }, [isSessionActive]);

  const handleTeacherLogin = () => {
    if (teacherPassword === TEACHER_PASSWORD) {
      setIsLoggedIn(true);
      setUserType('teacher');
      setTeacherPassword('');
    } else {
      alert('Hatalı şifre!');
    }
  };

  const handleStudentLogin = () => {
    const student = studentList.find(s => s.number === loginStudentNumber);
    if (student) {
      setIsLoggedIn(true);
      setUserType('student');
      setLoggedInStudentNumber(loginStudentNumber);
      setLoginStudentNumber('');
    } else {
      alert('Öğrenci numarası bulunamadı!');
    }
  };

  const handleLogout = () => {
    setIsLoggedIn(false);
    setUserType(null);
    setLoggedInStudentNumber('');
    if (userType === 'teacher') {
      endSession();
    }
  };

  const startSession = () => {
    const code = generateSessionCode();
    setCurrentSessionCode(code);
    setIsSessionActive(true);
    setSessionStartTime(new Date());
    setTimeRemaining(10);
  };

  const endSession = () => {
    setIsSessionActive(false);
    setCurrentSessionCode('');
    setSessionStartTime(null);
    setTimeRemaining(10);
  };

  const addStudent = () => {
    if (studentName && studentNumber) {
      setStudentList([...studentList, { name: studentName, number: studentNumber, department: '' }]);
      setStudentName('');
      setStudentNumber('');
    }
  };

  const removeStudent = (index) => {
    setStudentList(studentList.filter((_, i) => i !== index));
  };

  const markAttendance = () => {
    if (sessionCode.toUpperCase() === currentSessionCode && loggedInStudentNumber) {
      const key = `${currentWeek}-${loggedInStudentNumber}`;
      
      // Aynı öğrenci aynı haftada tekrar yoklama veremez
      if (attendanceRecords[key]) {
        alert('Bu hafta zaten yoklama verdiniz!');
        return;
      }

      const now = new Date();
      const timeDiff = (now - sessionStartTime) / 1000 / 60;
      const status = timeDiff <= 10 ? 'present' : 'late';
      
      setAttendanceRecords({
        ...attendanceRecords,
        [key]: {
          week: currentWeek,
          studentNumber: loggedInStudentNumber,
          status,
          time: now.toLocaleTimeString('tr-TR')
        }
      });
      
      setSessionCode('');
      alert(`✅ Yoklama başarıyla kaydedildi!\nDurum: ${status === 'present' ? 'Zamanında' : 'Geç'}`);
    } else {
      alert('❌ Kod hatalı veya süresi dolmuş!');
    }
  };

  const getAttendanceStats = () => {
    const stats = {};
    studentList.forEach(student => {
      let present = 0, late = 0, absent = 0;
      for (let w = 1; w <= currentWeek; w++) {
        const key = `${w}-${student.number}`;
        const record = attendanceRecords[key];
        if (record) {
          if (record.status === 'present') present++;
          else if (record.status === 'late') late++;
        } else {
          absent++;
        }
      }
      stats[student.number] = { present, late, absent };
    });
    return stats;
  };

  const exportToCSV = () => {
    let csv = 'Öğrenci No,Öğrenci Adı,Bölüm,';
    for (let w = 1; w <= currentWeek; w++) {
      csv += `Hafta ${w},`;
    }
    csv += 'Toplam Geldi,Geç Kaldı,Gelmedi\n';

    const stats = getAttendanceStats();
    studentList.forEach(student => {
      csv += `${student.number},${student.name},${student.department},`;
      for (let w = 1; w <= currentWeek; w++) {
        const key = `${w}-${student.number}`;
        const record = attendanceRecords[key];
        csv += record ? (record.status === 'present' ? '✓,' : 'G,') : 'X,';
      }
      const s = stats[student.number];
      csv += `${s.present},${s.late},${s.absent}\n`;
    });

    const blob = new Blob([csv], { type: 'text/csv;charset=utf-8;' });
    const link = document.createElement('a');
    link.href = URL.createObjectURL(blob);
    link.download = `${courseName || 'yoklama'}_hafta${currentWeek}.csv`;
    link.click();
  };

  const stats = getAttendanceStats();
  const currentStudent = studentList.find(s => s.number === loggedInStudentNumber);

  // Giriş Ekranı
  if (!isLoggedIn) {
    return (
      <div className="min-h-screen bg-gradient-to-br from-blue-50 via-indigo-50 to-purple-50 flex items-center justify-center p-4">
        <div className="max-w-4xl w-full grid md:grid-cols-2 gap-6">
          {/* Öğretmen Girişi */}
          <div className="bg-white rounded-2xl shadow-2xl overflow-hidden border-2 border-indigo-200">
            <div className="bg-gradient-to-r from-indigo-600 to-purple-600 p-6 text-white text-center">
              <Lock className="mx-auto mb-3" size={48} />
              <h2 className="text-2xl font-bold">Öğretmen Girişi</h2>
              <p className="text-sm opacity-90 mt-1">Yönetim paneline erişim</p>
            </div>
            <div className="p-8 space-y-4">
              <div>
                <label className="block font-semibold mb-2 text-gray-700">Şifre</label>
                <input
                  type="password"
                  value={teacherPassword}
                  onChange={(e) => setTeacherPassword(e.target.value)}
                  onKeyPress={(e) => e.key === 'Enter' && handleTeacherLogin()}
                  placeholder="Öğretmen şifrenizi girin"
                  className="w-full px-4 py-3 border-2 border-gray-300 rounded-lg focus:ring-2 focus:ring-indigo-500 focus:border-indigo-500"
                />
              </div>
              <button
                onClick={handleTeacherLogin}
                className="w-full bg-gradient-to-r from-indigo-600 to-purple-600 text-white py-3 rounded-lg font-bold hover:from-indigo-700 hover:to-purple-700 transition"
              >
                👨‍🏫 Giriş Yap
              </button>
              <p className="text-xs text-gray-500 text-center mt-4">Demo şifre: ogretmen123</p>
            </div>
          </div>

          {/* Öğrenci Girişi */}
          <div className="bg-white rounded-2xl shadow-2xl overflow-hidden border-2 border-green-200">
            <div className="bg-gradient-to-r from-green-500 to-emerald-500 p-6 text-white text-center">
              <Users className="mx-auto mb-3" size={48} />
              <h2 className="text-2xl font-bold">Öğrenci Girişi</h2>
              <p className="text-sm opacity-90 mt-1">Yoklama vermek için</p>
            </div>
            <div className="p-8 space-y-4">
              <div>
                <label className="block font-semibold mb-2 text-gray-700">Öğrenci Numarası</label>
                <input
                  type="text"
                  value={loginStudentNumber}
                  onChange={(e) => setLoginStudentNumber(e.target.value)}
                  onKeyPress={(e) => e.key === 'Enter' && handleStudentLogin()}
                  placeholder="Örn: 21070001004"
                  className="w-full px-4 py-3 border-2 border-gray-300 rounded-lg focus:ring-2 focus:ring-green-500 focus:border-green-500"
                />
              </div>
              <button
                onClick={handleStudentLogin}
                className="w-full bg-gradient-to-r from-green-500 to-emerald-500 text-white py-3 rounded-lg font-bold hover:from-green-600 hover:to-emerald-600 transition"
              >
                🎓 Giriş Yap
              </button>
              <p className="text-xs text-gray-500 text-center mt-4">Öğrenci numaranızı kullanarak giriş yapın</p>
            </div>
          </div>
        </div>
      </div>
    );
  }

  // Öğretmen Paneli
  if (userType === 'teacher') {
    return (
      <div className="min-h-screen bg-gradient-to-br from-blue-50 to-indigo-100 p-4">
        <div className="max-w-6xl mx-auto">
          <div className="bg-white rounded-2xl shadow-2xl overflow-hidden">
            {/* Header */}
            <div className="bg-gradient-to-r from-indigo-600 to-purple-600 p-6 text-white flex justify-between items-center">
              <div>
                <h1 className="text-3xl font-bold mb-1">📚 Öğretmen Paneli</h1>
                <p className="opacity-90">Yoklama yönetim sistemi</p>
              </div>
              <button
                onClick={handleLogout}
                className="flex items-center gap-2 bg-white/20 hover:bg-white/30 px-4 py-2 rounded-lg transition"
              >
                <LogOut size={20} />
                Çıkış
              </button>
            </div>

            <div className="p-6 space-y-6">
              {/* Course Setup */}
              <div className="bg-blue-50 p-4 rounded-lg">
                <label className="block font-semibold mb-2 text-gray-700">Ders Adı</label>
                <input
                  type="text"
                  value={courseName}
                  onChange={(e) => setCourseName(e.target.value)}
                  placeholder="Örn: Matematik 101"
                  className="w-full px-4 py-2 border border-gray-300 rounded-lg focus:ring-2 focus:ring-indigo-500"
                />
              </div>

              {/* Week Selection */}
              <div className="flex items-center gap-4 bg-purple-50 p-4 rounded-lg">
                <Calendar className="text-purple-600" size={24} />
                <div className="flex-1">
                  <label className="block font-semibold mb-2 text-gray-700">Hafta</label>
                  <input
                    type="number"
                    min="1"
                    max="14"
                    value={currentWeek}
                    onChange={(e) => setCurrentWeek(parseInt(e.target.value))}
                    className="w-32 px-4 py-2 border border-gray-300 rounded-lg"
                  />
                </div>
                <div className="text-right">
                  <div className="text-2xl font-bold text-purple-600">{currentWeek}. Hafta</div>
                  <div className="text-sm text-gray-600">Öğrenci: {studentList.length}</div>
                </div>
              </div>

              {/* Session Control */}
              <div className="bg-gradient-to-r from-green-50 to-emerald-50 p-6 rounded-lg border-2 border-green-200">
                <h3 className="font-bold text-lg mb-4 flex items-center gap-2">
                  <Clock className="text-green-600" />
                  Yoklama Oturumu
                </h3>
                {!isSessionActive ? (
                  <button
                    onClick={startSession}
                    className="w-full bg-gradient-to-r from-green-600 to-emerald-600 text-white py-4 rounded-lg font-bold hover:from-green-700 hover:to-emerald-700 transition text-lg"
                  >
                    ▶ Oturumu Başlat
                  </button>
                ) : (
                  <div className="space-y-4">
                    <div className="bg-white p-6 rounded-xl border-4 border-green-500 shadow-lg">
                      <div className="text-center">
                        <div className="text-sm text-gray-600 mb-2">AKTİF KOD</div>
                        <div className="text-6xl font-bold text-green-600 tracking-widest mb-3">
                          {currentSessionCode}
                        </div>
                        <div className="flex items-center justify-center gap-3 text-lg">
                          <Clock className="text-orange-500" size={24} />
                          <span className="font-bold text-orange-600">
                            {timeRemaining} saniye
                          </span>
                        </div>
                        <div className="text-xs text-gray-500 mt-3">
                          Başlangıç: {sessionStartTime?.toLocaleTimeString('tr-TR')}
                        </div>
                      </div>
                    </div>
                    <div className="bg-yellow-50 p-3 rounded-lg border border-yellow-200 text-center text-sm">
                      ⚠️ Kod her 10 saniyede otomatik değişir
                    </div>
                    <button
                      onClick={endSession}
                      className="w-full bg-red-600 text-white py-3 rounded-lg font-bold hover:bg-red-700 transition"
                    >
                      ⏹ Oturumu Sonlandır
                    </button>
                  </div>
                )}
              </div>

              {/* Student Management */}
              <div className="bg-gray-50 p-4 rounded-lg">
                <h3 className="font-bold text-lg mb-3 flex items-center gap-2">
                  <Users className="text-indigo-600" />
                  Öğrenci Yönetimi
                </h3>
                <div className="flex gap-2 mb-4">
                  <input
                    type="text"
                    value={studentName}
                    onChange={(e) => setStudentName(e.target.value)}
                    placeholder="Öğrenci Adı"
                    className="flex-1 px-4 py-2 border rounded-lg"
                  />
                  <input
                    type="text"
                    value={studentNumber}
                    onChange={(e) => setStudentNumber(e.target.value)}
                    placeholder="Numara"
                    className="w-40 px-4 py-2 border rounded-lg"
                  />
                  <button
                    onClick={addStudent}
                    className="bg-indigo-600 text-white px-6 py-2 rounded-lg font-semibold hover:bg-indigo-700"
                  >
                    + Ekle
                  </button>
                </div>

                <div className="space-y-2 max-h-64 overflow-y-auto">
                  {studentList.map((student, index) => (
                    <div key={index} className="flex items-center justify-between bg-white p-3 rounded-lg">
                      <div>
                        <div className="font-semibold">{student.name}</div>
                        <div className="text-sm text-gray-600">{student.number}</div>
                      </div>
                      <button
                        onClick={() => removeStudent(index)}
                        className="text-red-600 hover:bg-red-50 px-3 py-1 rounded"
                      >
                        Sil
                      </button>
                    </div>
                  ))}
                </div>
              </div>

              {/* Statistics */}
              <div className="bg-indigo-50 p-4 rounded-lg">
                <h3 className="font-bold text-lg mb-3">📊 Devamsızlık İstatistikleri</h3>
                <div className="space-y-2 max-h-96 overflow-y-auto">
                  {studentList.map(student => {
                    const s = stats[student.number] || { present: 0, late: 0, absent: 0 };
                    return (
                      <div key={student.number} className="bg-white p-3 rounded-lg flex justify-between items-center">
                        <div className="font-semibold">{student.name}</div>
                        <div className="flex gap-4 text-sm">
                          <span className="flex items-center gap-1 text-green-600">
                            <CheckCircle size={16} /> {s.present}
                          </span>
                          <span className="flex items-center gap-1 text-yellow-600">
                            <Clock size={16} /> {s.late}
                          </span>
                          <span className="flex items-center gap-1 text-red-600">
                            <XCircle size={16} /> {s.absent}
                          </span>
                        </div>
                      </div>
                    );
                  })}
                </div>
              </div>

              {/* Export */}
              <button
                onClick={exportToCSV}
                className="w-full bg-gradient-to-r from-indigo-600 to-purple-600 text-white py-3 rounded-lg font-bold hover:from-indigo-700 hover:to-purple-700 transition flex items-center justify-center gap-2"
              >
                <Download size={20} />
                CSV'ye Aktar
              </button>
            </div>
          </div>
        </div>
      </div>
    );
  }

  // Öğrenci Paneli
  return (
    <div className="min-h-screen bg-gradient-to-br from-green-50 to-emerald-100 p-4">
      <div className="max-w-2xl mx-auto">
        <div className="bg-white rounded-2xl shadow-2xl overflow-hidden">
          {/* Header */}
          <div className="bg-gradient-to-r from-green-500 to-emerald-500 p-6 text-white flex justify-between items-center">
            <div>
              <h1 className="text-2xl font-bold mb-1">🎓 Öğrenci Paneli</h1>
              <p className="opacity-90">{currentStudent?.name}</p>
              <p className="text-sm opacity-80">{currentStudent?.number}</p>
            </div>
            <button
              onClick={handleLogout}
              className="flex items-center gap-2 bg-white/20 hover:bg-white/30 px-4 py-2 rounded-lg transition"
            >
              <LogOut size={20} />
              Çıkış
            </button>
          </div>

          <div className="p-6 space-y-6">
            {/* Attendance Status */}
            <div className="bg-gradient-to-r from-blue-50 to-purple-50 p-6 rounded-xl border-2 border-blue-200">
              <h3 className="font-bold text-lg mb-4 flex items-center gap-2">
                <Calendar className="text-blue-600" />
                Devamsızlık Durumunuz
              </h3>
              <div className="flex justify-around">
                <div className="text-center">
                  <div className="text-3xl font-bold text-green-600">
                    {stats[loggedInStudentNumber]?.present || 0}
                  </div>
                  <div className="text-sm text-gray-600">Geldi</div>
                </div>
                <div className="text-center">
                  <div className="text-3xl font-bold text-yellow-600">
                    {stats[loggedInStudentNumber]?.late || 0}
                  </div>
                  <div className="text-sm text-gray-600">Geç</div>
                </div>
                <div className="text-center">
                  <div className="text-3xl font-bold text-red-600">
                    {stats[loggedInStudentNumber]?.absent || 0}
                  </div>
                  <div className="text-sm text-gray-600">Yok</div>
                </div>
              </div>
            </div>

            {/* Attendance Form */}
            {isSessionActive ? (
              <div className="space-y-4">
                <div className="bg-green-50 p-4 rounded-lg border-2 border-green-300 text-center">
                  <div className="text-green-700 font-bold mb-2">✅ Oturum Aktif</div>
                  <div className="text-sm text-gray-600">
                    Öğretmenin tahtada gösterdiği kodu girin
                  </div>
                </div>

                {attendanceRecords[`${currentWeek}-${loggedInStudentNumber}`] ? (
                  <div className="bg-blue-50 p-6 rounded-xl border-2 border-blue-300 text-center">
                    <CheckCircle className="mx-auto text-blue-600 mb-3" size={48} />
                    <h3 className="text-xl font-bold text-blue-700 mb-2">
                      Bu Hafta Yoklama Verildi!
                    </h3>
                    <div className="text-sm text-gray-600">
                      Kayıt zamanı: {attendanceRecords[`${currentWeek}-${loggedInStudentNumber}`].time}
                    </div>
                  </div>
                ) : (
                  <>
                    <div className="bg-white p-6 rounded-xl border-2 border-gray-300 shadow-lg">
                      <label className="block font-bold mb-3 text-gray-700 text-center">
                        Tahtadaki Kodu Girin
                      </label>
                      <input
                        type="text"
                        value={sessionCode}
                        onChange={(e) => setSessionCode(e.target.value.toUpperCase())}
                        placeholder="6 haneli kod"
                        maxLength="6"
                        className="w-full px-6 py-4 border-2 border-gray-300 rounded-lg focus:ring-4 focus:ring-green-300 focus:border-green-500 text-2xl font-mono text-center uppercase tracking-widest"
                      />
                      <div className="text-xs text-gray-500 text-center mt-2">
                        Kod her 10 saniyede değişir
                      </div>
                    </div>

                    <button
                      onClick={markAttendance}
                      className="w-full bg-gradient-to-r from-green-600 to-emerald-600 text-white py-4 rounded-xl font-bold text-lg hover:from-green-700 hover:to-emerald-700 transition shadow-lg"
                    >
                      ✓ Yoklamaya Katıl
                    </button>
                  </>
                )}
              </div>
            ) : (
              <div className="bg-yellow-50 border-2 border-yellow-300 p-6 rounded-xl text-center">
                <XCircle className="mx-auto text-yellow-600 mb-3" size={48} />
                <h3 className="text-lg font-bold text-yellow-700 mb-2">
                  Oturum Aktif Değil
                </h3>
                <p className="text-sm text-gray-600">
                  Öğretmen henüz yoklama oturumu başlatmadı.<br />
                  Lütfen bekleyin.
                </p>
              </div>
            )}

            {/* Weekly Status */}
            <div className="bg-gray-50 p-4 rounded-lg">
              <h3 className="font-bold mb-3 flex items-center gap-2">
                <Calendar className="text-indigo-600" />
                Haftalık Durum
              </h3>
              <div className="grid grid-cols-7 gap-2">
                {Array.from({ length: currentWeek }, (_, i) => {
                  const weekNum = i + 1;
                  const key = `${weekNum}-${loggedInStudentNumber}`;
                  const record = attendanceRecords[key];
                  
                  let bgColor = 'bg-red-100 border-red-300';
                  let icon = '✗';
                  let textColor = 'text-red-600';
                  
                  if (record) {
                    if (record.status === 'present') {
                      bgColor = 'bg-green-100 border-green-300';
                      icon = '✓';
                      textColor = 'text-green-600';
                    } else {
                      bgColor = 'bg-yellow-100 border-yellow-300';
                      icon = 'G';
                      textColor = 'text-yellow-600';
                    }
                  }
                  
                  return (
                    <div
                      key={weekNum}
                      className={`${bgColor} border-2 rounded-lg p-2 text-center`}
                    >
                      <div className="text-xs text-gray-600">H{weekNum}</div>
                      <div className={`text-lg font-bold ${textColor}`}>{icon}</div>
                    </div>
                  );
                })}
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  );
}