<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iOyKpxd)"><path fill="url(#iKMi2ZH)" clip-rule="evenodd" class="y8szpx1to"/><path fill="url(#iZQuiZd)" clip-rule="evenodd" class="y8szpx1to"/><path fill="url(#ieRHnje)" clip-rule="evenodd" class="y8szpx1to"/><path fill="url(#iXbFrFc)" clip-rule="evenodd" class="y8szpx1to"/><path fill="url(#ieCeiLb)" clip-rule="evenodd" class="y8szpx1to"/><path fill="url(#i1rLm1D)" clip-rule="evenodd" class="y8szpx1to"/><path fill="url(#iVGmcBe)" clip-rule="evenodd" class="y8szpx1to"/><path fill="url(#icyZood)" clip-rule="evenodd" class="y8szpx1to"/><path fill="url(#iozLbff)" clip-rule="evenodd" class="y8szpx1to"/><path fill="url(#izqMzee)" clip-rule="evenodd" class="y8szpx1to"/><path fill="url(#iwXvNhd)" clip-rule="evenodd" class="y8szpx1to"/></g><g filter="url(#iAscTXd)"><path class="voegjzb9j"/><path fill="url(#irEOifd)" class="b-6_k7b0g"/></g><path fill="url(#iCP0v4G)" class="b-6_k7b0g"/><path fill="url(#ic1vv5T)" class="b-6_k7b0g"/><path fill="url(#iyiGEtb)" class="b-6_k7b0g"/><path fill="url(#iKcLcde)" class="b-6_k7b0g"/><g filter="url(#il0GfOe)"><path class="puix6x09i"/><path fill="url(#iRlV5Zd)" class="ls4aqdb9u"/></g><path class="br4c1ob1g"/><path fill="url(#iITYAbb)" class="hrtei6-4e"/><path fill="url(#iiYTi1b)" class="hrtei6-4e"/><path fill="url(#iKeKdcc)" class="fdtzvco7b"/><path fill="url(#iJOlbhd)" class="g5r_tqbfx"/><path fill="url(#i85fHYi)" class="g5r_tqbfx"/><g filter="url(#iFqo7xe)"><path fill="url(#i9Jcyqc)" class="s94il2b-u"/><path fill="url(#irK61gc)" class="s94il2b-u"/></g><g filter="url(#ibnOcee)"><circle fill="url(#i4Zburd)" class="muj581mlw"/></g><g filter="url(#iTIjdbc)"><circle fill="url(#iJWZvpd)" class="dpdr7tmvr"/></g><g filter="url(#ikS2YIe)"><circle fill="url(#iBzbYEb)" class="qeda3yjxr"/></g><rect fill="url(#iSCw0bb)" transform="rotate(26.595 20.662 12.85)" class="mfbmcht5h"/><g filter="url(#i1GngEd)"><path fill="url(#iHhOgbu)" class="fdcs8elnr"/></g><path class="ru-ifdbbv"/><path fill="url(#iU5Zf3d)" class="m_84pgbbs"/><g filter="url(#i7Os9hc)"><path class="c4xnsojyi"/><path fill="url(#ijGh6lb)" class="z965t0boy"/><path fill="url(#iDlic4l)" class="z965t0boy"/></g><g filter="url(#iC3xNud)"><path fill="url(#iWYgeqe)" class="d0gdshbdt"/><path fill="url(#iv7gCCE)" class="d0gdshbdt"/><path fill="url(#i0HlTxe)" class="d0gdshbdt"/></g><path fill="url(#iHqsxEe)" class="d0gdshbdt"/><path fill="url(#iVuQjqd)" class="j66sw2b6j"/><path fill="url(#ipJlYSd)" class="j66sw2b6j"/><path clip-rule="evenodd" class="kri8vcc4o"/><path fill="url(#iR4950b)" clip-rule="evenodd" class="u3v6ddfew"/><path clip-rule="evenodd" class="afdkdch4d"/><path fill="url(#ixTdsYb)" clip-rule="evenodd" class="zt0-34bqy"/><path clip-rule="evenodd" class="p32at6nrh"/><path fill="url(#iZDP40b)" clip-rule="evenodd" class="xtoj2rbva"/><path clip-rule="evenodd" class="b4iezgrul"/><path fill="url(#iCZ4uGQ)" clip-rule="evenodd" class="xhceozbrw"/><path class="ue3okb08d"/><path fill="url(#igYcSCb)" class="p-aoy09lz"/><g filter="url(#iGhm3ad)"><path fill="url(#igaYcee)" class="bxutmbcso"/></g><g filter="url(#igPEkJd)"><path fill="url(#imxLxFd)" class="oa7a6in9y"/></g><g filter="url(#idBpBde)"><path stroke="url(#iSuq2Jv)" class="x5mqywbvi"/></g><g filter="url(#id9bfzX)"><path fill="url(#iuoHWeb)" class="v9-28obio"/></g><g filter="url(#i7Mv1UH)"><path fill="url(#imIRjvc)" class="ovfj0nbso"/><path fill="url(#iP2ukwR)" class="ovfj0nbso"/></g><g filter="url(#iQ6F7Kd)"><path class="l48d_ppjn"/><path fill="url(#i7vL9Lb)" class="fxsid9bpl"/></g><g filter="url(#iyP0YRc)"><path class="wl-9cybsp"/><path fill="url(#iIbh07q)" class="wst6qwyoz"/></g><g filter="url(#iacO4jk)"><path fill="url(#iANjSNp)" class="t3n-zfbhp"/><path fill="url(#iuo6V2d)" class="t3n-zfbhp"/><path fill="url(#iUhHWee)" class="t3n-zfbhp"/><path fill="url(#iEwdOXc)" class="t3n-zfbhp"/><path fill="url(#ijo3jFb)" class="t3n-zfbhp"/><path fill="url(#iUe2dod)" class="t3n-zfbhp"/><path fill="url(#iyuMIre)" class="t3n-zfbhp"/></g><path fill="url(#iDIuwfI)" class="t3n-zfbhp"/><path fill="url(#ixuPPoe)" class="t3n-zfbhp"/><g filter="url(#iVfXNTc)"><path class="z_rl6hb_s"/></g><g filter="url(#iXfDdYK)"><path class="xxtz6acwj"/><path fill="url(#i59Ctpd)" class="dzwwr7b9s"/><path fill="url(#iJSgkiY)" class="dzwwr7b9s"/><path fill="url(#ik77Spp)" class="dzwwr7b9s"/><path fill="url(#ilsYVyc)" class="dzwwr7b9s"/></g><g filter="url(#icDVHec)"><path stroke="url(#iZyDcRd)" class="oy-d0n7vv"/></g><path class="x-yetsb8e"/><g filter="url(#iQlZ0kh)"><path class="bwak7bcgw"/></g><g filter="url(#iasp4ue)"><path class="fftpgc0ap"/></g><g filter="url(#izvufvb)"><path class="e3e9zzbdu"/></g><g filter="url(#ilW4Ade)"><path clip-rule="evenodd" class="eaapqh9jq"/></g><path class="fuyp2bcql"/><path fill="url(#i5uHahd)" class="j87twj-bn"/><path class="lg-lmd_kk"/><g filter="url(#iSBNMMd)"><path class="eoutn1akt"/><path fill="url(#io96gPe)" class="r1errob0p"/></g><g filter="url(#ioxkT1d)"><path fill="url(#ih58DPd)" class="e0w3yoblr"/></g><path class="u42rp3blu"/><path fill="url(#if4dAPc)" class="c8kvk6blp"/><path class="iw906xb2v"/><g filter="url(#ie1qqVc)"><path fill="url(#iVuPKcb)" class="b4lltqzns"/></g><g filter="url(#ipQicpc)"><ellipse transform="rotate(-27.914 12.928 5.707)" class="fr193bbyu"/><ellipse fill="url(#iB5yped)" transform="rotate(-27.914 12.928 5.707)" class="z0o5mxfla"/></g><g filter="url(#iVaujue)"><path class="tzxol0bae"/><path fill="url(#iOlyxlc)" class="nvjm2-pkf"/><path fill="url(#ijPS1Qb)" class="nvjm2-pkf"/></g><g filter="url(#iulIgEb)"><path class="y0jp6_b2b"/></g><defs><radialGradient id="iZQuiZd" cx="0" cy="0" r="1" gradientTransform="matrix(-.2709 2.04681 -2.55688 -.3384 13.895 7.14)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="ieRHnje" cx="0" cy="0" r="1" gradientTransform="matrix(-1.29434 .87291 -1.14694 -1.70066 12.63 7.26)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iXbFrFc" cx="0" cy="0" r="1" gradientTransform="matrix(-.58695 .76756 -.58938 -.4507 11.855 6.117)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="ieCeiLb" cx="0" cy="0" r="1" gradientTransform="matrix(-.57944 .94815 -.66789 -.40816 12.06 5.206)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="i1rLm1D" cx="0" cy="0" r="1" gradientTransform="matrix(.61705 1.1739 -1.62956 .85657 12.45 2.4)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iVGmcBe" cx="0" cy="0" r="1" gradientTransform="matrix(-.64711 .64716 -.9044 -.90433 16.649 3.333)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="icyZood" cx="0" cy="0" r="1" gradientTransform="matrix(-.82772 .2408 -.50218 -1.72614 17.401 5.635)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iozLbff" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26417 .31606 -.40261 -1.61036 17.13 7.17)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="izqMzee" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 9.702 -3.507)scale(1.25722 .99439)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iwXvNhd" cx="0" cy="0" r="1" gradientTransform="matrix(.67519 .07081 -.11473 1.094 11.27 5.618)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iCP0v4G" cx="0" cy="0" r="1" gradientTransform="matrix(3.84373 7.81251 -11.27829 5.54887 20.985 21.81)" gradientUnits="userSpaceOnUse"><stop offset=".7" class="er0557b1s"/><stop offset=".913" class="qg0p67bet"/></radialGradient><radialGradient id="iyiGEtb" cx="0" cy="0" r="1" gradientTransform="matrix(3.5625 -6.125 3.8162 2.21963 22.204 21.967)" gradientUnits="userSpaceOnUse"><stop class="vj0--9brr"/><stop offset="1" class="holozbkuz"/></radialGradient><radialGradient id="iKcLcde" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 -12.12496 23.16436 4.11944 23.61 28.811)" gradientUnits="userSpaceOnUse"><stop offset=".931" class="ro0d6lgcg"/><stop offset="1" class="ghsb7_-dv"/></radialGradient><radialGradient id="iRlV5Zd" cx="0" cy="0" r="1" gradientTransform="matrix(1.09706 3.375 -16.62038 5.40254 16.17 25.248)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="czuo201bw"/><stop offset="1" class="ecs-9379l"/></radialGradient><radialGradient id="iITYAbb" cx="0" cy="0" r="1" gradientTransform="matrix(-.83721 2.51163 -.64638 -.21546 9.761 25.18)" gradientUnits="userSpaceOnUse"><stop offset=".261" class="vxxc7i85i"/><stop offset="1" class="tu701m2xi"/></radialGradient><radialGradient id="i85fHYi" cx="0" cy="0" r="1" gradientTransform="matrix(-.73437 -1.28906 .42946 -.24466 23.579 25.514)" gradientUnits="userSpaceOnUse"><stop class="kzew_oulk"/><stop offset="1" class="ui2bqrbyd"/></radialGradient><radialGradient id="irK61gc" cx="0" cy="0" r="1" gradientTransform="rotate(-110.045 20.756 2.839)scale(2.46162 1.62421)" gradientUnits="userSpaceOnUse"><stop class="of_rz239k"/><stop offset="1" class="lvv_hcmig"/></radialGradient><radialGradient id="i4Zburd" cx="0" cy="0" r="1" gradientTransform="rotate(146.686 11.209 11.158)scale(2.36974 1.91739)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="b07bm3qgt"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="iJWZvpd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.47607 .92253 -.74644 -1.19432 29.42 12.597)" gradientUnits="userSpaceOnUse"><stop class="fdd72shlv"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="iBzbYEb" cx="0" cy="0" r="1" gradientTransform="rotate(147.995 12.162 9.193)scale(1.52552 1.23432)" gradientUnits="userSpaceOnUse"><stop class="fdd72shlv"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="iSCw0bb" cx="0" cy="0" r="1" gradientTransform="matrix(-.06342 .73199 -.55995 -.04852 21.024 13.149)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="jalmfobon"/><stop offset="1" class="fhgc0ib0i"/></radialGradient><radialGradient id="iHhOgbu" cx="0" cy="0" r="1" gradientTransform="rotate(139.295 9.191 10.945)scale(2.80315 2.75944)" gradientUnits="userSpaceOnUse"><stop class="gttado_ri"/><stop offset="1" class="s1_qcx0nn"/></radialGradient><radialGradient id="iU5Zf3d" cx="0" cy="0" r="1" gradientTransform="matrix(-.01563 -.84376 1.95707 -.03625 7.864 15.076)" gradientUnits="userSpaceOnUse"><stop class="vevwxpb8j"/><stop offset="1" class="w9ndm1bxw"/></radialGradient><radialGradient id="ijGh6lb" cx="0" cy="0" r="1" gradientTransform="rotate(142.524 4.92 6.738)scale(4.72526 1.21438)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="hiph0yb8z"/><stop offset="1" class="nng6piu-d"/></radialGradient><radialGradient id="iDlic4l" cx="0" cy="0" r="1" gradientTransform="rotate(103.462 2.319 10.573)scale(4.16121 1.35388)" gradientUnits="userSpaceOnUse"><stop class="rjhj4ebho"/><stop offset="1" class="m0m5thktx"/></radialGradient><radialGradient id="iv7gCCE" cx="0" cy="0" r="1" gradientTransform="matrix(4.2188 -6.78122 .53719 .3342 11.328 24.467)" gradientUnits="userSpaceOnUse"><stop class="zhpuq6bwb"/><stop offset="1" class="lrsiznbuc"/></radialGradient><radialGradient id="i0HlTxe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.49191 -2.04898 0 13.776 7.647)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="sz7_smkrr"/><stop offset="1" class="rqh0k2bpm"/></radialGradient><radialGradient id="iHqsxEe" cx="0" cy="0" r="1" gradientTransform="matrix(1.125 -.625 2.3294 4.19292 17.339 21.28)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="tn---htwd"/><stop offset="1" class="accyaboul"/></radialGradient><radialGradient id="ipJlYSd" cx="0" cy="0" r="1" gradientTransform="matrix(3.55689 1.62587 -1.10084 2.4083 18.61 10.794)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="ns_rnx4db"/><stop offset="1" class="airol1bay"/><stop offset="1" class="cfcr9ub1k"/></radialGradient><radialGradient id="iR4950b" cx="0" cy="0" r="1" gradientTransform="rotate(-138.814 5.313 5.993)scale(1.66096 2.09285)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="s1mjb1beh"/><stop offset=".769" class="cd88em0te"/></radialGradient><radialGradient id="ixTdsYb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.24388 -.94214 1.33264 -1.75944 5.77 14.73)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="s1mjb1beh"/><stop offset=".769" class="cd88em0te"/></radialGradient><radialGradient id="iZDP40b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.23007 -1.01775 1.46904 -1.7755 5.598 15.297)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="s1mjb1beh"/><stop offset=".769" class="cd88em0te"/></radialGradient><radialGradient id="iCZ4uGQ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04688 -.89062 1.29178 -1.51843 5.802 15.529)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="s1mjb1beh"/><stop offset=".769" class="cd88em0te"/></radialGradient><radialGradient id="igYcSCb" cx="0" cy="0" r="1" gradientTransform="matrix(.14063 .15625 -.6598 .59382 7.037 14.82)" gradientUnits="userSpaceOnUse"><stop class="cl_02q7-e"/><stop offset="1" class="uzhwu5bek"/></radialGradient><radialGradient id="igaYcee" cx="0" cy="0" r="1" gradientTransform="rotate(135 10.5 15.423)scale(15.9541 20.2938)" gradientUnits="userSpaceOnUse"><stop class="q7quaubxc"/><stop offset="1" class="kf-sl5b6g"/></radialGradient><radialGradient id="imIRjvc" cx="0" cy="0" r="1" gradientTransform="matrix(.82023 -.91429 1.1163 1.00146 16.054 6.456)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="w--6bgeqj"/><stop offset=".944" class="sheftacio"/></radialGradient><radialGradient id="iP2ukwR" cx="0" cy="0" r="1" gradientTransform="matrix(.59071 .3311 -.0936 .167 16.306 5.263)" gradientUnits="userSpaceOnUse"><stop class="ynae43ovp"/><stop offset="1" class="v-9tn59hb"/></radialGradient><radialGradient id="i7vL9Lb" cx="0" cy="0" r="1" gradientTransform="matrix(.67787 -.05042 .03942 .5299 16.002 6.068)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="k2oqpgb0o"/><stop offset="1" class="dkw8bsvxv"/></radialGradient><radialGradient id="iIbh07q" cx="0" cy="0" r="1" gradientTransform="matrix(-.5418 0 0 -.42742 11.965 6.018)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="b55qklbsj"/><stop offset="1" class="uaoaczbhz"/></radialGradient><radialGradient id="iANjSNp" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 7.023 4.569)scale(3.21529 4.3036)" gradientUnits="userSpaceOnUse"><stop class="v5rheyc4i"/><stop offset="1" class="wum9l96_j"/></radialGradient><radialGradient id="iuo6V2d" cx="0" cy="0" r="1" gradientTransform="rotate(172.574 7.538 3.697)scale(1.56704 1.72974)" gradientUnits="userSpaceOnUse"><stop class="z-rzt8b_f"/><stop offset="1" class="tk20gvbnd"/></radialGradient><radialGradient id="iUhHWee" cx="0" cy="0" r="1" gradientTransform="matrix(.58695 -1.70066 2.15782 .74473 12.962 9.066)" gradientUnits="userSpaceOnUse"><stop class="fvm07vbkd"/><stop offset="1" class="n1w64orcn"/></radialGradient><radialGradient id="iEwdOXc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.01906 -3.49467 0 14.03 5.679)" gradientUnits="userSpaceOnUse"><stop offset=".567" class="vrhnsgvqh"/><stop offset="1" class="iuch0hb0l"/></radialGradient><radialGradient id="ijo3jFb" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 7.103 3.998)scale(3.15945 5.43961)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="brg8dbpny"/><stop offset="1" class="d_t8kfbgb"/></radialGradient><radialGradient id="iUe2dod" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.51664 .63406 0 15.063 5.589)" gradientUnits="userSpaceOnUse"><stop class="e2earo80w"/><stop offset="1" class="xl9xm7bnj"/></radialGradient><radialGradient id="iyuMIre" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.58926 .67533 0 13.098 5.486)" gradientUnits="userSpaceOnUse"><stop class="suybu51ug"/><stop offset="1" class="intda8ekf"/></radialGradient><radialGradient id="iDIuwfI" cx="0" cy="0" r="1" gradientTransform="matrix(-.57703 0 0 -2.89376 16.317 6.256)" gradientUnits="userSpaceOnUse"><stop class="sqxrh1b6n"/><stop offset="1" class="eodwsybla"/></radialGradient><radialGradient id="ixuPPoe" cx="0" cy="0" r="1" gradientTransform="rotate(71.834 4.396 10.55)scale(1.89002 3.29263)" gradientUnits="userSpaceOnUse"><stop class="f_q-3cc4h"/><stop offset="1" class="s44y8_wdc"/></radialGradient><radialGradient id="i59Ctpd" cx="0" cy="0" r="1" gradientTransform="matrix(-.20452 -.91767 .28281 -.06303 14.382 6.584)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xbgj88f0b"/><stop offset="1" class="y_9l2i5ww"/></radialGradient><radialGradient id="ilsYVyc" cx="0" cy="0" r="1" gradientTransform="matrix(-.34991 0 0 -.09783 14.274 6.678)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="i5uHahd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3634 -.57802 0 15.009 5.75)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="io96gPe" cx="0" cy="0" r="1" gradientTransform="matrix(-.104 -.13402 .1845 -.14318 14.907 5.787)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="if4dAPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3634 -.57803 0 13.05 5.75)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iB5yped" cx="0" cy="0" r="1" gradientTransform="matrix(-.00347 -.22155 .26632 -.00417 12.922 5.85)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iOlyxlc" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 6.67 5.91)scale(2.1877 3.57677)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="ijPS1Qb" cx="0" cy="0" r="1" gradientTransform="rotate(98.746 5.936 7.372)scale(.62103 1.33611)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="iOyKpxd" width="6.992" height="7.492" x="10.659" y="1.439" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23004"/></filter><filter id="iAscTXd" width="23.977" height="13.398" x="6.016" y="16.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.729412 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23004"/></filter><filter id="il0GfOe" width="20.681" height="10.082" x="6.11" y="20.291" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23004" stdDeviation=".75"/></filter><filter id="iFqo7xe" width="24.344" height="8.644" x="2.007" y="21.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.415686 0 0 0 0 0.839216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23004"/></filter><filter id="ibnOcee" width="2.686" height="2.686" x="24.571" y="13.41" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23004"/></filter><filter id="iTIjdbc" width="2.186" height="2.186" x="27.821" y="11.711" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23004"/></filter><filter id="ikS2YIe" width="1.928" height="1.928" x="25.946" y="9.754" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23004"/></filter><filter id="i1GngEd" width="2.857" height="2.898" x="20.532" y="12.178" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.572549 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23004"/></filter><filter id="i7Os9hc" width="5.571" height="6.952" x="7.773" y="7.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.6"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.219608 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23004"/></filter><filter id="iC3xNud" width="14.97" height="18.153" x="8.427" y="7.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.470588 0 0 0 0 0.741176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23004"/></filter><filter id="iGhm3ad" width="17.737" height="14.8" x="13.579" y="15.892" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23004" stdDeviation="1"/></filter><filter id="igPEkJd" width="6.506" height="14.75" x="14.572" y="7.451" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23004" stdDeviation=".375"/></filter><filter id="idBpBde" width="5.506" height="5.421" x="17.991" y="7.526" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23004" stdDeviation=".3"/></filter><filter id="id9bfzX" width="1.595" height="1.445" x="11.204" y="5.295" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.682353 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23004"/></filter><filter id="i7Mv1UH" width="1.445" height="1.695" x="15.475" y="5.045" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23004"/></filter><filter id="iQ6F7Kd" width="1.964" height="1.964" x="15.215" y="5.036" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23004" stdDeviation=".25"/></filter><filter id="iyP0YRc" width="1.764" height="1.764" x="11.053" y="5.136" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23004" stdDeviation=".2"/></filter><filter id="iacO4jk" width="4.575" height="5.283" x="11.742" y="3.815" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23004"/></filter><filter id="iVfXNTc" width="1.843" height="2.204" x="13.036" y="5.291" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23004" stdDeviation=".25"/></filter><filter id="iXfDdYK" width="1.043" height="1.404" x="13.508" y="5.629" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23004" stdDeviation=".05"/></filter><filter id="icDVHec" width="1.883" height=".906" x="13.088" y="6.962" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23004" stdDeviation=".05"/></filter><filter id="iQlZ0kh" width="1.458" height=".577" x="14.343" y="5.387" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23004"/></filter><filter id="iasp4ue" width="1.458" height=".577" x="12.259" y="5.387" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23004"/></filter><filter id="izvufvb" width="1.211" height=".6" x="12.32" y="4.638" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23004"/></filter><filter id="ilW4Ade" width="1.211" height=".6" x="14.752" y="4.638" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23004"/></filter><filter id="iSBNMMd" width=".463" height=".423" x="14.625" y="5.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23004" stdDeviation=".05"/></filter><filter id="ioxkT1d" width=".62" height=".63" x="14.947" y="5.476" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23004" stdDeviation=".1"/></filter><filter id="ie1qqVc" width=".662" height=".687" x="12.953" y="5.447" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23004" stdDeviation=".1"/></filter><filter id="ipQicpc" width=".52" height=".426" x="12.668" y="5.494" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23004" stdDeviation=".05"/></filter><filter id="iVaujue" width="4.139" height="2.721" x="12.441" y="2.354" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23004"/><feGaussianBlur result="effect2_foregroundBlur_3987_23004" stdDeviation=".075"/></filter><filter id="iulIgEb" width="3.712" height="2.34" x="13.356" y="2.896" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23004" stdDeviation=".375"/></filter><linearGradient id="iKMi2ZH" x1="16.137" x2="13.082" y1="2.896" y2="8.555" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="irEOifd" x1="7.172" x2="16.735" y1="29.405" y2="29.405" gradientUnits="userSpaceOnUse"><stop class="e_8e_fe6a"/><stop offset="1" class="t2zfh_b3c"/></linearGradient><linearGradient id="ic1vv5T" x1="16.86" x2="16.766" y1="30.311" y2="28.686" gradientUnits="userSpaceOnUse"><stop offset=".178" class="oste98bcz"/><stop offset="1" class="ojj5yabro"/></linearGradient><linearGradient id="iiYTi1b" x1="7.833" x2="8.372" y1="25.966" y2="26.146" gradientUnits="userSpaceOnUse"><stop offset=".283" class="q2kjmzqur"/><stop offset="1" class="atc_6-nza"/><stop offset="1" class="h31kj0t6r"/></linearGradient><linearGradient id="iKeKdcc" x1="21.172" x2="19.469" y1="21.967" y2="23.053" gradientUnits="userSpaceOnUse"><stop class="ion1yqb0q"/><stop offset="1" class="r9287rbao"/></linearGradient><linearGradient id="iJOlbhd" x1="22.095" x2="23.329" y1="24.873" y2="26.155" gradientUnits="userSpaceOnUse"><stop class="jikp3gouc"/><stop offset="1" class="esa0tobpk"/></linearGradient><linearGradient id="i9Jcyqc" x1="5.891" x2="25.735" y1="29.28" y2="22.373" gradientUnits="userSpaceOnUse"><stop class="d9q_ne9mx"/><stop offset="1" class="y110racyj"/></linearGradient><linearGradient id="iWYgeqe" x1="15.777" x2="15.777" y1="7.647" y2="25.608" gradientUnits="userSpaceOnUse"><stop class="t_t1uhgaw"/><stop offset="1" class="wlohty-lv"/></linearGradient><linearGradient id="iVuQjqd" x1="23.651" x2="16.517" y1="12.543" y2="8.59" gradientUnits="userSpaceOnUse"><stop class="g55u5uboh"/><stop offset=".91" class="hq3x-3bjw"/></linearGradient><linearGradient id="imxLxFd" x1="17.826" x2="20.269" y1="8.201" y2="21.438" gradientUnits="userSpaceOnUse"><stop class="xf-olmy6i"/><stop offset="1" class="nb49g6u5x"/></linearGradient><linearGradient id="iSuq2Jv" x1="22.438" x2="18.766" y1="11.92" y2="8.03" gradientUnits="userSpaceOnUse"><stop class="o-7v_hpgv"/><stop offset="1" class="qosi95ahb"/></linearGradient><linearGradient id="iuoHWeb" x1="11.204" x2="12.533" y1="6.057" y2="6.057" gradientUnits="userSpaceOnUse"><stop class="ixw8njbyx"/><stop offset="1" class="me4c4fyoe"/></linearGradient><linearGradient id="iJSgkiY" x1="13.608" x2="14.03" y1="6.615" y2="6.615" gradientUnits="userSpaceOnUse"><stop class="l38p1-72g"/><stop offset="1" class="njp0-cbrk"/></linearGradient><linearGradient id="ik77Spp" x1="14.03" x2="14.03" y1="6.974" y2="6.7" gradientUnits="userSpaceOnUse"><stop class="vdvey0c5l"/><stop offset="1" class="tddz0-g7t"/></linearGradient><linearGradient id="iZyDcRd" x1="13.552" x2="13.759" y1="7.607" y2="7.287" gradientUnits="userSpaceOnUse"><stop class="b5nknil5b"/><stop offset=".663" class="prv6psg5p"/></linearGradient><linearGradient id="ih58DPd" x1="15.358" x2="15.218" y1="5.774" y2="5.86" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iVuPKcb" x1="13.384" x2="13.243" y1="5.773" y2="5.86" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-surfing-light" /></template>
<style>
.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.accyaboul {
  stop-color: var(--svg-color--593b9d, #593B9D);
  stop-opacity: 0;
}

.afdkdch4d {
  fill: var(--svg-color--f3bea7, #F3BEA7);
  fill-rule: evenodd;
  d: path("M5.404 14.18s.02-.028.083-.08a2.1 2.1 0 0 1 1.279-.412a.375.375 0 1 0 .024-.749a2.84 2.84 0 0 0-1.323.295c-.176.087-.33.185-.452.284c-.11.089-.234.211-.296.355a.375.375 0 0 0 .685.306");
}

.airol1bay {
  stop-color: var(--svg-color--815ecd, #815ECD);
  stop-opacity: 0;
}

.atc_6-nza {
  stop-color: var(--svg-color--f2b790, #F2B790);
  stop-opacity: 0;
}

.b-6_k7b0g {
  d: path("M19.75 29.789H6.017c3.433-1.326 10.769-4.346 12.657-5.818c2.359-1.84 2.937-3.291 4.109-4.976s2.062-2.293 3.922-2.036c1.691.235 3.164 1.575 3.289 4.04c0 4.593-2.74 6.555-4.164 7.511c-1.907 1.279-4.625 1.326-6.078 1.279");
}

.b07bm3qgt {
  stop-color: var(--svg-color--64ddff, #64DDFF);
}

.b4iezgrul {
  fill: var(--svg-color--f3bea7, #F3BEA7);
  fill-rule: evenodd;
  d: path("M5.611 14.986a.375.375 0 0 1-.69-.296c.093-.216.328-.445.6-.604a1.76 1.76 0 0 1 1.119-.237a.375.375 0 1 1-.099.744a1 1 0 0 0-.641.14a1 1 0 0 0-.215.164a.5.5 0 0 0-.074.089");
}

.b4lltqzns {
  d: path("M13.415 5.888c0-.129-.105-.215-.133-.24l-.13.124l.08.162z");
}

.b55qklbsj {
  stop-color: var(--svg-color--bc8272, #BC8272);
  stop-opacity: 0;
}

.b5nknil5b {
  stop-color: var(--svg-color--eabbab, #EABBAB);
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.br4c1ob1g {
  fill: var(--svg-color--f0b8a0, #F0B8A0);
  d: path("m7.305 27.389l1.172-2.39l1.766.304v1.04z");
}

.brg8dbpny {
  stop-color: var(--svg-color--e2a895, #E2A895);
  stop-opacity: 0;
}

.bwak7bcgw {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M14.543 5.762c.12-.21.3-.375.69-.375a.75.75 0 0 1 .482.166c.12.097.104.222.01.269l-.249.142c-.292-.094-.616-.107-.933-.202");
}

.bxutmbcso {
  d: path("M26.485 24.374c.981-2.279.626-3.887.055-5.014c-.474-.936-.003-1.662 1.018-1.42c.737.173 1.364.693 1.54 1.43c.721 3.025-.313 6.182-3.582 7.816c-2.95 1.475-7.854 1.594-9.937 1.469c3 0 9.804-1.723 10.906-4.282");
}

.c4xnsojyi {
  fill: var(--svg-color--7a5cb9, #7A5CB9);
  d: path("M10.684 11.737c-.967.714-2.204 1.017-2.723 1.058c-.13 1 .107 1.771.243 2.031c.3-.027 1.148-.109 2.5-.718c1.679-.757 2.458-1.804 2.64-2.246l-.28-3.387c-.376 1.031-1.005 2.246-2.38 3.262");
}

.c8kvk6blp {
  d: path("M13.049 5.536a.4.4 0 0 0-.386.505h.773a.402.402 0 0 0-.387-.505");
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cd88em0te {
  stop-color: var(--svg-color--d89c92, #D89C92);
  stop-opacity: 0;
}

.cfcr9ub1k {
  stop-color: var(--svg-color--6845b9, #6845B9);
  stop-opacity: 0;
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cl_02q7-e {
  stop-color: var(--svg-color--f6c1b0, #F6C1B0);
}

.czuo201bw {
  stop-color: var(--svg-color--37a9ff, #37A9FF);
  stop-opacity: 0;
}

.d_t8kfbgb {
  stop-color: var(--svg-color--e2a895, #E2A895);
}

.d0gdshbdt {
  d: path("M12.759 11.694c-.432-1.716.169-3.162.507-3.485l2.344-.562h1.742c1.524 0 2.822.189 4.203 1.258c1.354 1.047 1.622 2.799 1.589 3.592a.05.05 0 0 1-.051.046l-1.989-.074a.05.05 0 0 1-.049-.058c.038-.371-.066-1.273-1-2.014c-.606-.481-1.519-.532-2.146-.494a.373.373 0 0 0-.323.498c.316.955.84 2.513 1.212 3.52c.546 1.484-.11 2.952.375 4.484c.377 1.191 1.203 2.418 1.636 2.92a.04.04 0 0 1-.013.063l-1.834.852a.04.04 0 0 1-.048-.01c-1.848-2.158-2.5-3.826-2.562-3.99c-.062-.163-.23-.53-.574-.53c-.275 0-.59.35-.809.73l-4.667 7.137a.05.05 0 0 1-.056.02l-1.783-.52a.05.05 0 0 1-.032-.068c1.499-3.163 4.542-9.51 4.773-10.058c.21-.5.181-.916.14-1.085c-.03-.13-.218-.711-.585-2.172");
}

.d9q_ne9mx {
  stop-color: var(--svg-color--f54696, #F54696);
}

.dkw8bsvxv {
  stop-color: var(--svg-color--f5b99d, #F5B99D);
}

.dpdr7tmvr {
  cx: 28.864px;
  cy: 12.854px;
  r: 1.043px;
}

.dzwwr7b9s {
  d: path("m13.858 5.856l-.238.763a.242.242 0 0 0 .233.314h.353c.166 0 .283-.16.234-.314l-.238-.763c-.052-.17-.29-.17-.344 0");
}

.e_8e_fe6a {
  stop-color: var(--svg-color--2d7cf2, #2D7CF2);
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0w3yoblr {
  d: path("M15.367 5.883a.4.4 0 0 0-.104-.207l-.116.127l.052.103z");
}

.e2earo80w {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
}

.e3e9zzbdu {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M12.505 5.22h-.002a.12.12 0 0 1-.124-.206l.002-.001l.004-.003l.015-.008l.052-.026a2 2 0 0 1 .184-.073a1.26 1.26 0 0 1 .596-.049a.12.12 0 0 1-.041.237a1 1 0 0 0-.482.042a1 1 0 0 0-.194.081z");
}

.eaapqh9jq {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m15.705 5.014l-.062.103za.12.12 0 0 1-.123.207l-.003-.002l-.05-.026a1 1 0 0 0-.154-.06a1 1 0 0 0-.481-.042a.12.12 0 1 1-.042-.237c.23-.04.444 0 .596.05a1.5 1.5 0 0 1 .25.106l.005.003z");
}

.ecs-9379l {
  stop-color: var(--svg-color--37a9ff, #37A9FF);
}

.eodwsybla {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
  stop-opacity: 0;
}

.eoutn1akt {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M14.98 5.62c.03.038-.03.085-.098.136c-.068.05-.118.086-.147.048s.004-.11.071-.161c.068-.05.146-.06.175-.023");
}

.er0557b1s {
  stop-color: var(--svg-color--3eb9ff, #3EB9FF);
  stop-opacity: 0;
}

.esa0tobpk {
  stop-color: var(--svg-color--9157c5, #9157C5);
}

.f_q-3cc4h {
  stop-color: var(--svg-color--a47463, #A47463);
}

.fdcs8elnr {
  d: path("M20.68 13.89c.256-.588.373-1.22.399-1.462l2.047.024c.046.268-.04.583-.079.703c.088.322.037.687 0 .829c-.054.225-.178.713-.238.86c-.074.183-.183.246-.348.23a.4.4 0 0 1-.148-.043a.3.3 0 0 0-.23-.019a.43.43 0 0 1-.227.02a.43.43 0 0 1-.204-.113a.22.22 0 0 0-.195-.06a.5.5 0 0 1-.226.004a.36.36 0 0 1-.172-.115a.22.22 0 0 0-.175-.07c-.085.007-.183.002-.235-.042c-.098-.082-.219-.175.031-.746");
}

.fdd72shlv {
  stop-color: var(--svg-color--65e0ff, #65E0FF);
}

.fdtzvco7b {
  d: path("M19.837 23.053a29 29 0 0 1-.907-.867l1.867-.883c.075.131.51.8.72 1.117z");
}

.fftpgc0ap {
  fill: var(--svg-color--272528, #272528);
  d: path("M13.517 5.762c-.12-.21-.3-.375-.69-.375a.74.74 0 0 0-.482.166c-.12.097-.104.222-.01.269l.249.142c.293-.094.616-.107.933-.202");
}

.fhgc0ib0i {
  stop-color: var(--svg-color--dd937e, #DD937E);
}

.fr193bbyu {
  cx: 12.928px;
  cy: 5.707px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.175px;
  ry: 0.088px;
}

.ft5dv1b6b {
  fill: none;
}

.fuyp2bcql {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.103 5.413c.293 0 .541.203.608.476a.123.123 0 0 1-.12.153H14.59a.103.103 0 0 1-.102-.122a.63.63 0 0 1 .615-.507");
}

.fvm07vbkd {
  stop-color: var(--svg-color--b87c92, #B87C92);
}

.fxsid9bpl {
  d: path("M16.197 6.5a.482.482 0 1 0 0-.964a.482.482 0 0 0 0 .964");
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g55u5uboh {
  stop-color: var(--svg-color--896ad2, #896AD2);
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.g5r_tqbfx {
  d: path("m23.469 25.368l-.422-1.143l-2.351.536l2.225 1.1a.396.396 0 0 0 .547-.493");
}

.ghsb7_-dv {
  stop-color: var(--svg-color--66b4dd, #66B4DD);
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gttado_ri {
  stop-color: var(--svg-color--faccbd, #FACCBD);
}

.h31kj0t6r {
  stop-color: var(--svg-color--fac2a5, #FAC2A5);
  stop-opacity: 0;
}

.hiph0yb8z {
  stop-color: var(--svg-color--8069a8, #8069A8);
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.holozbkuz {
  stop-color: var(--svg-color--4db5e2, #4DB5E2);
  stop-opacity: 0;
}

.hq3x-3bjw {
  stop-color: var(--svg-color--8c6dd3, #8C6DD3);
}

.hrtei6-4e {
  d: path("m7.305 27.389l1.172-2.39l1.766.304v1.04z");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.intda8ekf {
  stop-color: var(--svg-color--d09790, #D09790);
  stop-opacity: 0;
}

.ion1yqb0q {
  stop-color: var(--svg-color--f6cbb9, #F6CBB9);
}

.iuch0hb0l {
  stop-color: var(--svg-color--b4807e, #B4807E);
}

.iw906xb2v {
  fill: var(--svg-color--000, #000);
  d: path("M13.278 5.936a.23.23 0 0 0-.23-.23a.228.228 0 0 0-.203.335h.406a.2.2 0 0 0 .027-.105");
}

.ixw8njbyx {
  stop-color: var(--svg-color--cc9987, #CC9987);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j66sw2b6j {
  d: path("M17.568 10.318a.37.37 0 0 1 .34-.415c.628-.038 1.541.013 2.147.494c.934.74 1.038 1.643 1 2.014c-.003.03.02.057.05.058l1.987.075a.05.05 0 0 0 .052-.047c.033-.793-.235-2.545-1.589-3.592c-1.381-1.07-2.68-1.258-4.203-1.258h-.39c-.157 1.285.25 2.193.606 2.671");
}

.j87twj-bn {
  d: path("M15.01 5.536a.4.4 0 0 1 .385.505h-.772a.4.4 0 0 1 .387-.505");
}

.jalmfobon {
  stop-color: var(--svg-color--e19b84, #E19B84);
}

.jikp3gouc {
  stop-color: var(--svg-color--b041ab, #B041AB);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.k2oqpgb0o {
  stop-color: var(--svg-color--f4b89e, #F4B89E);
  stop-opacity: 0;
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kf-sl5b6g {
  stop-color: var(--svg-color--67ecff, #67ECFF);
  stop-opacity: 0;
}

.kri8vcc4o {
  fill: var(--svg-color--f3bea7, #F3BEA7);
  fill-rule: evenodd;
  d: path("M7.127 13.585c-.941-.284-1.295.01-1.388.119a.375.375 0 0 1-.57-.488c.328-.383 1.014-.699 2.174-.35a.375.375 0 0 1-.216.719");
}

.kzew_oulk {
  stop-color: var(--svg-color--b77dc7, #B77DC7);
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l38p1-72g {
  stop-color: var(--svg-color--dfa791, #DFA791);
}

.l48d_ppjn {
  fill: var(--svg-color--f6bca5, #F6BCA5);
  d: path("M16.197 6.5a.482.482 0 1 0 0-.964a.482.482 0 0 0 0 .964");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lg-lmd_kk {
  fill: var(--svg-color--000, #000);
  d: path("M14.78 5.936a.23.23 0 0 1 .23-.23a.228.228 0 0 1 .203.335h-.405a.2.2 0 0 1-.027-.105");
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lrsiznbuc {
  stop-color: var(--svg-color--623f8d, #623F8D);
  stop-opacity: 0;
}

.ls4aqdb9u {
  d: path("m21.985 27.374l-14.375 1.5c4.687-2.24 11.938-4.407 14.375-6.188c1.826-1.334 2.896-1.2 3.281.563c.219 1-1.031 3.625-3.281 4.125");
}

.lvv_hcmig {
  stop-color: var(--svg-color--9eaef5, #9EAEF5);
  stop-opacity: 0;
}

.m_84pgbbs {
  d: path("M7.602 12.817h.594c-.106.669.012 1.608.114 1.996c-1.006.131-1.637-.108-1.856-.246l-.11-1.461c.332-.256.977-.3 1.258-.29");
}

.m0m5thktx {
  stop-color: var(--svg-color--572cad, #572CAD);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.me4c4fyoe {
  stop-color: var(--svg-color--ac7864, #AC7864);
}

.mfbmcht5h {
  width: 0.599px;
  height: 1.031px;
  x: 20.662px;
  y: 12.85px;
  rx: 0.299px;
}

.muj581mlw {
  cx: 25.864px;
  cy: 14.803px;
  r: 1.293px;
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n-jrenige {
  stop-color: var(--svg-color--36b0fc, #36B0FC);
}

.n1w64orcn {
  stop-color: var(--svg-color--b87c92, #B87C92);
  stop-opacity: 0;
}

.nb49g6u5x {
  stop-color: var(--svg-color--8b79ca, #8B79CA);
}

.njp0-cbrk {
  stop-color: var(--svg-color--dfa791, #DFA791);
  stop-opacity: 0;
}

.nng6piu-d {
  stop-color: var(--svg-color--8069a8, #8069A8);
  stop-opacity: 0;
}

.ns_rnx4db {
  stop-color: var(--svg-color--6845b9, #6845B9);
}

.nvjm2-pkf {
  d: path("M13.76 2.52c-.51-.112-.966.395-1.019.583c.473 1.592 1.667 1.505 2.847 1.374c.706-.079.782.243.842.398c0-1.765-1.5-2.097-2.658-2.352z");
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.o-7v_hpgv {
  stop-color: var(--svg-color--9577dc, #9577DC);
}

.oa7a6in9y {
  d: path("M16.782 13.49c-.65-1.28-1.166-3.184-1.443-4.422a.714.714 0 0 1 .588-.856c.447-.075.855.271.91.722c.205 1.698.95 3.373 1.445 4.682c.578 1.531.312 1.062.234 3.515c-.057 1.782 1.266 3.25 1.813 4.11l-.407.21c-.609-.827-2.203-2.945-2.203-4.85c0-1.792.063-1.141-.937-3.11");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.of_rz239k {
  stop-color: var(--svg-color--9eaef5, #9EAEF5);
}

.ojj5yabro {
  stop-color: var(--svg-color--7f8fff, #7F8FFF);
  stop-opacity: 0;
}

.oste98bcz {
  stop-color: var(--svg-color--7f8fff, #7F8FFF);
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.ovfj0nbso {
  d: path("M16.197 6.74a.722.722 0 1 0 0-1.445a.722.722 0 0 0 0 1.445");
}

.oy-d0n7vv {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.03 7.325a1.36 1.36 0 0 1-.638-.155c-.064-.033-.131.04-.092.099a.867.867 0 0 0 1.46 0c.039-.061-.029-.132-.092-.099a1.35 1.35 0 0 1-.638.155Z");
}

.p-aoy09lz {
  d: path("M6.126 14.928c.125-.137.398-.46.52-.605c.23 0 .91-.067 1.198-.098c-.39.715-.84 1.004-1.074 1.195c-.316.211-.605 0-.644-.066c-.047-.047-.157-.254 0-.426");
}

.p32at6nrh {
  fill: var(--svg-color--f3bea7, #F3BEA7);
  fill-rule: evenodd;
  d: path("M5.25 14.708q-.005.007-.002 0a.375.375 0 0 1-.69-.295a1.2 1.2 0 0 1 .27-.354a2.6 2.6 0 0 1 .438-.328a2.5 2.5 0 0 1 1.336-.37a.375.375 0 1 1-.023.75a1.73 1.73 0 0 0-.927.263a1.8 1.8 0 0 0-.307.23a1 1 0 0 0-.095.104");
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.prv6psg5p {
  stop-color: var(--svg-color--eabbab, #EABBAB);
  stop-opacity: 0;
}

.puix6x09i {
  fill: var(--svg-color--1b71cc, #1B71CC);
  d: path("m21.985 27.374l-14.375 1.5c4.687-2.24 11.938-4.407 14.375-6.188c1.826-1.334 2.896-1.2 3.281.563c.219 1-1.031 3.625-3.281 4.125");
}

.q2kjmzqur {
  stop-color: var(--svg-color--fac2a5, #FAC2A5);
}

.q7quaubxc {
  stop-color: var(--svg-color--67ecff, #67ECFF);
}

.qeda3yjxr {
  cx: 26.86px;
  cy: 10.768px;
  r: 0.914px;
}

.qg0p67bet {
  stop-color: var(--svg-color--7196ff, #7196FF);
}

.qosi95ahb {
  stop-color: var(--svg-color--9577dc, #9577DC);
  stop-opacity: 0;
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r1errob0p {
  d: path("M14.98 5.62c.03.038-.03.085-.098.136c-.068.05-.118.086-.147.048s.004-.11.071-.161c.068-.05.146-.06.175-.023");
}

.r9287rbao {
  stop-color: var(--svg-color--d29a85, #D29A85);
}

.rjhj4ebho {
  stop-color: var(--svg-color--572cad, #572CAD);
}

.ro0d6lgcg {
  stop-color: var(--svg-color--66b4dd, #66B4DD);
  stop-opacity: 0;
}

.rqh0k2bpm {
  stop-color: var(--svg-color--6f43ac, #6F43AC);
  stop-opacity: 0;
}

.ru-ifdbbv {
  fill: var(--svg-color--f0bca4, #F0BCA4);
  d: path("M7.602 12.817h.594c-.106.669.012 1.608.114 1.996c-1.006.131-1.637-.108-1.856-.246l-.11-1.461c.332-.256.977-.3 1.258-.29");
}

.s1_qcx0nn {
  stop-color: var(--svg-color--e2a89d, #E2A89D);
}

.s1mjb1beh {
  stop-color: var(--svg-color--d89c92, #D89C92);
}

.s44y8_wdc {
  stop-color: var(--svg-color--a47463, #A47463);
  stop-opacity: 0;
}

.s94il2b-u {
  d: path("M24.458 21.303L2.29 28.992a.421.421 0 0 0 .138.819h3.948c.487 0 .968-.099 1.156-.156c5.922-2.016 17.406-5.86 18.176-6.2c.443-.195.511-.378.605-.627v-.001c.094-.25.047-1.032-.5-1.454c-.437-.337-1.105-.184-1.355-.07");
}

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sqxrh1b6n {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.suybu51ug {
  stop-color: var(--svg-color--d09790, #D09790);
}

.sz7_smkrr {
  stop-color: var(--svg-color--6f43ac, #6F43AC);
}

.t_t1uhgaw {
  stop-color: var(--svg-color--8463ce, #8463CE);
}

.t2zfh_b3c {
  stop-color: var(--svg-color--2d7cf2, #2D7CF2);
  stop-opacity: 0;
}

.t3n-zfbhp {
  d: path("M11.746 5.45h.005l-.004-.118l-.005-.138c.01-.426.258-.59.364-.646l.023-.009l.023-.009c.24-.11.433-.302.534-.554l.037-.087a.118.118 0 0 1 .207-.023c.322.472.861.751 1.432.751h1.446c.08 0 .485.04.51.598l-.054 1.38c-.055 1.258-1.038 2.103-2.237 2.103s-2.182-.845-2.237-2.103z");
}

.tddz0-g7t {
  stop-color: var(--svg-color--d29394, #D29394);
  stop-opacity: 0;
}

.tk20gvbnd {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
  stop-opacity: 0;
}

.tn---htwd {
  stop-color: var(--svg-color--593b9d, #593B9D);
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tu701m2xi {
  stop-color: var(--svg-color--f4baa6, #F4BAA6);
  stop-opacity: 0;
}

.tzxol0bae {
  fill: var(--svg-color--2a2a2a, #2A2A2A);
  d: path("M13.76 2.52c-.51-.112-.966.395-1.019.583c.473 1.592 1.667 1.505 2.847 1.374c.706-.079.782.243.842.398c0-1.765-1.5-2.097-2.658-2.352z");
}

.u3v6ddfew {
  fill-rule: evenodd;
  d: path("M7.127 13.585c-.941-.284-1.295.01-1.388.119a.375.375 0 0 1-.57-.488c.328-.383 1.014-.699 2.174-.35a.375.375 0 0 1-.216.719");
}

.u42rp3blu {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.957 5.413a.63.63 0 0 0-.609.476c-.02.078.04.153.12.153h1.002a.103.103 0 0 0 .102-.122a.63.63 0 0 0-.615-.507");
}

.uaoaczbhz {
  stop-color: var(--svg-color--bc8272, #BC8272);
}

.ue3okb08d {
  fill: var(--svg-color--f0bca4, #F0BCA4);
  d: path("M6.126 14.928c.125-.137.398-.46.52-.605c.23 0 .91-.067 1.198-.098c-.39.715-.84 1.004-1.074 1.195c-.316.211-.605 0-.644-.066c-.047-.047-.157-.254 0-.426");
}

.ui2bqrbyd {
  stop-color: var(--svg-color--b77dc7, #B77DC7);
  stop-opacity: 0;
}

.uzhwu5bek {
  stop-color: var(--svg-color--f6c1b0, #F6C1B0);
  stop-opacity: 0;
}

.v-9tn59hb {
  stop-color: var(--svg-color--dba98b, #DBA98B);
  stop-opacity: 0;
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.v9-28obio {
  d: path("M11.926 6.74a.722.722 0 1 0 0-1.445a.722.722 0 0 0 0 1.445");
}

.vdvey0c5l {
  stop-color: var(--svg-color--d29394, #D29394);
}

.vevwxpb8j {
  stop-color: var(--svg-color--da9893, #DA9893);
}

.vj0--9brr {
  stop-color: var(--svg-color--4db5e2, #4DB5E2);
}

.voegjzb9j {
  fill: var(--svg-color--4bc4fd, #4BC4FD);
  d: path("M19.75 29.789H6.017c3.433-1.326 10.769-4.346 12.657-5.818c2.359-1.84 2.937-3.291 4.109-4.976s2.062-2.293 3.922-2.036c1.691.235 3.164 1.575 3.289 4.04c0 4.593-2.74 6.555-4.164 7.511c-1.907 1.279-4.625 1.326-6.078 1.279");
}

.vrhnsgvqh {
  stop-color: var(--svg-color--cd9897, #CD9897);
  stop-opacity: 0;
}

.vxxc7i85i {
  stop-color: var(--svg-color--f4baa6, #F4BAA6);
}

.w--6bgeqj {
  stop-color: var(--svg-color--e5b1a5, #E5B1A5);
}

.w9ndm1bxw {
  stop-color: var(--svg-color--da9893, #DA9893);
  stop-opacity: 0;
}

.wl-9cybsp {
  fill: var(--svg-color--c58c80, #C58C80);
  d: path("M11.935 6.5a.482.482 0 1 0 0-.965a.482.482 0 0 0 0 .965");
}

.wlohty-lv {
  stop-color: var(--svg-color--6247a5, #6247A5);
}

.wst6qwyoz {
  d: path("M11.935 6.5a.482.482 0 1 0 0-.965a.482.482 0 0 0 0 .965");
}

.wum9l96_j {
  stop-color: var(--svg-color--d59f97, #D59F97);
}

.x-yetsb8e {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M14.03 7.325a1.36 1.36 0 0 1-.638-.155c-.064-.033-.131.04-.092.099a.867.867 0 0 0 1.46 0c.039-.061-.029-.132-.092-.099a1.35 1.35 0 0 1-.638.155");
}

.x5mqywbvi {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.594 8.327c1.209-.021 3.782.828 4.104 4");
}

.xbgj88f0b {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xf-olmy6i {
  stop-color: var(--svg-color--9a7ce0, #9A7CE0);
}

.xhceozbrw {
  fill-rule: evenodd;
  d: path("M5.611 14.986a.375.375 0 0 1-.69-.296c.093-.216.328-.445.6-.604a1.76 1.76 0 0 1 1.119-.237a.375.375 0 1 1-.099.744a1 1 0 0 0-.641.14a1 1 0 0 0-.215.164a.5.5 0 0 0-.074.089");
}

.xl9xm7bnj {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
  stop-opacity: 0;
}

.xtoj2rbva {
  fill-rule: evenodd;
  d: path("M5.25 14.708q-.005.007-.002 0a.375.375 0 0 1-.69-.295a1.2 1.2 0 0 1 .27-.354a2.6 2.6 0 0 1 .438-.328a2.5 2.5 0 0 1 1.336-.37a.375.375 0 1 1-.023.75a1.73 1.73 0 0 0-.927.263a1.8 1.8 0 0 0-.307.23a1 1 0 0 0-.095.104");
}

.xxtz6acwj {
  fill: var(--svg-color--f1c4b2, #F1C4B2);
  d: path("m13.858 5.856l-.238.763a.242.242 0 0 0 .233.314h.353c.166 0 .283-.16.234-.314l-.238-.763c-.052-.17-.29-.17-.344 0");
}

.y_9l2i5ww {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
  stop-opacity: 0;
}

.y0jp6_b2b {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m15.11 4.14l-.64.118a.309.309 0 1 1-.056-.612h1.051c.622 0 .828.626.853.84a1.41 1.41 0 0 0-1.208-.345");
}

.y110racyj {
  stop-color: var(--svg-color--84a6e9, #84A6E9);
}

.y8szpx1to {
  fill-rule: evenodd;
  d: path("M17.256 6.65a1.48 1.48 0 0 0 .025-1.226h.002a1.4 1.4 0 0 0-.126-.23l-.001-.002a1.45 1.45 0 0 1-.236-.795v-.004c0-.818-.664-1.482-1.482-1.482a.24.24 0 0 1-.204-.104a1.484 1.484 0 0 0-2.408 0a.25.25 0 0 1-.205.104h-.038c-.8.021-1.443.676-1.443 1.482v.004c0 .282-.081.559-.236.795v.002a1.48 1.48 0 0 0-.1 1.457a.23.23 0 0 1 0 .204a1.443 1.443 0 0 0 1.3 2.076h3.852a1.443 1.443 0 0 0 1.3-2.076a.23.23 0 0 1 0-.204m-5.504-1.2h-.006l.538 1.058c.056 1.259.547 0 1.746 0c1.2 0 1.722 1.4 1.778.143l.51-1.436c-.024-.559-.43-.598-.51-.598h-1.446c-.57 0-1.11-.28-1.432-.751a.118.118 0 0 0-.207.023l-.037.087a1.03 1.03 0 0 1-.58.572c-.106.055-.354.22-.364.646l.005.138z");
}

.ynae43ovp {
  stop-color: var(--svg-color--dba98b, #DBA98B);
}

.z_rl6hb_s {
  fill: var(--svg-color--d19590, #D19590);
  d: path("m13.854 5.918l-.307.763a.242.242 0 0 0 .234.314h.353c.165 0 .282-.16.233-.314l-.238-.763c-.051-.17-.222-.17-.275 0");
}

.z-rzt8b_f {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
}

.z0o5mxfla {
  cx: 12.928px;
  cy: 5.707px;
  rx: 0.175px;
  ry: 0.088px;
}

.z965t0boy {
  d: path("M10.684 11.737c-.967.714-2.204 1.017-2.723 1.058c-.13 1 .107 1.771.243 2.031c.3-.027 1.148-.109 2.5-.718c1.679-.757 2.458-1.804 2.64-2.246l-.28-3.387c-.376 1.031-1.005 2.246-2.38 3.262");
}

.zhpuq6bwb {
  stop-color: var(--svg-color--623f8d, #623F8D);
}

.zt0-34bqy {
  fill-rule: evenodd;
  d: path("M5.404 14.18s.02-.028.083-.08a2.1 2.1 0 0 1 1.279-.412a.375.375 0 1 0 .024-.749a2.84 2.84 0 0 0-1.323.295c-.176.087-.33.185-.452.284c-.11.089-.234.211-.296.355a.375.375 0 0 0 .685.306");
}

</style>
