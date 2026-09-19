<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#imlGAOe)"><path fill="url(#iswxPLd)" clip-rule="evenodd" class="whdc-5b4w"/><path fill="url(#ibsuvWc)" clip-rule="evenodd" class="whdc-5b4w"/><path fill="url(#i72ZUkd)" clip-rule="evenodd" class="whdc-5b4w"/><path fill="url(#iLkDw3b)" clip-rule="evenodd" class="whdc-5b4w"/><path fill="url(#iki48BK)" clip-rule="evenodd" class="whdc-5b4w"/><path fill="url(#iHRo5Mb)" clip-rule="evenodd" class="whdc-5b4w"/><path fill="url(#iXG558d)" clip-rule="evenodd" class="whdc-5b4w"/><path fill="url(#iRrohzc)" clip-rule="evenodd" class="whdc-5b4w"/><path fill="url(#ipK38ad)" clip-rule="evenodd" class="whdc-5b4w"/><path fill="url(#iG1Unmd)" clip-rule="evenodd" class="whdc-5b4w"/></g><rect fill="url(#iBifC1c)" transform="rotate(26.961 19.37 13.476)" class="e2cbcwbro"/><g filter="url(#iBbGMtd)"><path class="w-wyxqbcb"/></g><circle fill="url(#inFRzLc)" class="pid-4m06y"/><circle fill="url(#ikT3wpb)" class="pid-4m06y"/><circle fill="url(#ipd3rHo)" class="pid-4m06y"/><circle fill="url(#ieUwNdb)" class="pid-4m06y"/><g filter="url(#iBBT3ud)"><path fill="url(#iWmx2lc)" class="ek5bxabzl"/></g><path fill="url(#ifKQLew)" class="c7tegqbne"/><path fill="url(#iUeJ2Sb)" class="c7tegqbne"/><path fill="url(#iP5V8Vd)" class="al5lvkbaq"/><path fill="url(#iqsv5Db)" class="al5lvkbaq"/><g filter="url(#iFklhFe)"><path fill="url(#iLF0nzb)" class="r6_hcsbxi"/><path fill="url(#iYUXpwc)" class="r6_hcsbxi"/><path fill="url(#iLV9ctc)" class="r6_hcsbxi"/></g><g filter="url(#i0ClwLb)"><path fill="url(#iforYlw)" class="ah2pisbqb"/><path fill="url(#inONwub)" class="ah2pisbqb"/></g><path fill="url(#iVuFPpe)" class="ktiqp3mew"/><path fill="url(#iKFMiMe)" class="ktiqp3mew"/><path fill="url(#ivkbt6S)" class="ziv54kk1v"/><path fill="url(#iXXJehd)" class="ziv54kk1v"/><path fill="url(#ijJ6cKc)" class="ziv54kk1v"/><path fill="url(#igATwqb)" class="ziv54kk1v"/><path class="y74gd5bcp"/><path fill="url(#is0WZfd)" class="uv36sqbhc"/><path fill="url(#ijCvQjy)" class="uv36sqbhc"/><path fill="url(#iqzarsk)" class="uv36sqbhc"/><g filter="url(#iyfF6de)"><path class="liuw-nhbd"/><path fill="url(#icubEce)" class="wbh3f-b7s"/><path fill="url(#i6Gutbe)" class="wbh3f-b7s"/><path fill="url(#ijdo7Sd)" class="wbh3f-b7s"/></g><g filter="url(#iEMWerb)"><path fill="url(#iuKSyQd)" class="e28we4bnz"/><path fill="url(#iC1Fxvb)" class="e28we4bnz"/></g><g filter="url(#iDRHm1d)"><path fill="url(#iaRXfSt)" class="ub-9o4pik"/><path fill="url(#iXLciIc)" class="ub-9o4pik"/></g><g filter="url(#inwGsEb)"><path fill="url(#ihRkukc)" clip-rule="evenodd" class="m-h0k-bsf"/></g><path class="izewy3bwp"/><path fill="url(#iK1dmYb)" class="y3287vlxz"/><path fill="url(#iUHJpLd)" class="y3287vlxz"/><path clip-rule="evenodd" class="hnazsfbsb"/><path fill="url(#i4Y3dQd)" clip-rule="evenodd" class="rbd89zfgs"/><path clip-rule="evenodd" class="demh68bgv"/><path fill="url(#iiAKlHe)" clip-rule="evenodd" class="st-rm_qqx"/><path clip-rule="evenodd" class="log-m9nxt"/><path fill="url(#iEW2KXc)" clip-rule="evenodd" class="yxnqo2bds"/><path clip-rule="evenodd" class="v6h8iny7i"/><path fill="url(#ieJiSGR)" clip-rule="evenodd" class="dy6986bug"/><path fill="url(#iSBOL3v)" clip-rule="evenodd" class="u1t7v_b3t"/><g filter="url(#iw60Cac)"><path class="xpipdtb9t"/><path fill="url(#ilvXOyx)" class="gtp576ola"/></g><path fill="url(#iykYkLF)" class="gtp576ola"/><path fill="url(#i1bmqCd)" clip-rule="evenodd" class="m-h0k-bsf"/><g filter="url(#iQCRose)"><path class="ptg5rr5de"/></g><g filter="url(#igPvCbc)"><path class="jg8nvfbol"/><path fill="url(#iOJ29Xd)" class="y1djx2bua"/></g><g filter="url(#iA4fWjc)"><path fill="url(#irN4kmc)" class="dl0oclbay"/></g><g filter="url(#iN1EuQb)"><path fill="url(#itEhSzd)" class="pdil1tsmk"/><path fill="url(#iKvdW0d)" class="pdil1tsmk"/></g><g filter="url(#ix4IPwT)"><path class="acxmtrlex"/><path fill="url(#i53sVud)" class="otq0w83qz"/></g><g filter="url(#iXZ87me)"><path class="asssleb6w"/><path fill="url(#iZK3csb)" class="kdica8byl"/></g><g filter="url(#i7kuygU)"><path fill="url(#inlgawb)" class="m526cvbra"/><path fill="url(#iI3i2nd)" class="m526cvbra"/><path fill="url(#itPRvhe)" class="m526cvbra"/><path fill="url(#iGQkrzb)" class="m526cvbra"/><path fill="url(#i48b0Gd)" class="m526cvbra"/><path fill="url(#ivOvkce)" class="m526cvbra"/><path fill="url(#itYgifd)" class="m526cvbra"/></g><path fill="url(#iLXb9Sd)" class="oo7nk3bzn"/><path fill="url(#iiOdENl)" class="oo7nk3bzn"/><g filter="url(#iQZ9P9d)"><path class="nsr99pb0o"/></g><g filter="url(#iYtlzfd)"><path class="xcez8obke"/><path fill="url(#ia3kGxb)" class="j2gnpuyah"/><path fill="url(#iHrHYCe)" class="j2gnpuyah"/><path fill="url(#iCx9zob)" class="j2gnpuyah"/></g><g filter="url(#iNoGiOb)"><path stroke="url(#iRnfajo)" class="bqbx36b8n"/></g><path class="g30_hrb9q"/><g filter="url(#iwMEVxe)"><path class="qk3iylyni"/></g><g filter="url(#iktw7Xb)"><path class="oolpdvc_e"/></g><g filter="url(#i0yLwhb)"><path class="f513s74td"/></g><g filter="url(#iwGxVwb)"><path clip-rule="evenodd" class="feam4fbza"/></g><path class="zzb5anb_b"/><path fill="url(#i9muZVd)" class="jv-6hac0r"/><path class="t9az4wpbm"/><g filter="url(#iYFIZ3A)"><path class="cqr5aro8f"/><path fill="url(#izZiv6d)" class="bso4iybss"/></g><g filter="url(#icVTBnb)"><path fill="url(#i5Ri29d)" class="z7rtwjbyn"/></g><path class="xnrju8bbx"/><path fill="url(#ipmQK5h)" class="bjv4rmbti"/><path class="tokrlwc9z"/><g filter="url(#iG6LCgZ)"><path fill="url(#ih1ETXb)" class="gop4tkdej"/></g><g filter="url(#iwVkMhd)"><ellipse transform="rotate(-27.914 11.764 5.721)" class="dz7zwddgg"/><ellipse fill="url(#iCXplLc)" transform="rotate(-27.914 11.764 5.721)" class="km0jvbbqs"/></g><g filter="url(#iOv8ESb)"><path class="opsul3b2p"/></g><g filter="url(#iEPqLre)"><path class="zb4vi2bec"/></g><g filter="url(#ikosrEe)"><path fill="url(#iGWD65c)" class="m-uhwp86n"/><path fill="url(#iBCNJrc)" class="m-uhwp86n"/></g><g filter="url(#ih2syAc)"><path fill="url(#iluwzQb)" class="i21jitbel"/><path fill="url(#iwBJQvb)" class="i21jitbel"/><path fill="url(#ixAJQqe)" class="i21jitbel"/></g><g filter="url(#iqU1aUE)"><path class="f7g2qnjfz"/></g><defs><radialGradient id="ibsuvWc" cx="0" cy="0" r="1" gradientTransform="matrix(.80447 -1.67083 3.8096 1.83425 15.062 8.727)" gradientUnits="userSpaceOnUse"><stop class="rjxj417_v"/><stop offset="1" class="p1sg1mumi"/></radialGradient><radialGradient id="i72ZUkd" cx="0" cy="0" r="1" gradientTransform="matrix(-.8715 2.52046 -2.35931 -.81579 12.587 6.855)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="ta36f8b7v"/><stop offset="1" class="hcuenbefp"/></radialGradient><radialGradient id="iLkDw3b" cx="0" cy="0" r="1" gradientTransform="rotate(142.167 4.475 5.623)scale(1.84127 2.2665)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="hxuphr-8h"/><stop offset="1" class="v-9s4u7ch"/></radialGradient><radialGradient id="iki48BK" cx="0" cy="0" r="1" gradientTransform="rotate(125.038 3.733 5.844)scale(.82193 .7471)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="ybvptdnhb"/><stop offset="1" class="ue-yx0baa"/></radialGradient><radialGradient id="iHRo5Mb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0752 -.23979 .35249 -1.58057 10.908 5.455)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="sqmgyf2vi"/><stop offset="1" class="mvuactshi"/></radialGradient><radialGradient id="iXG558d" cx="0" cy="0" r="1" gradientTransform="matrix(.9979 1.46197 -2.55134 1.74146 11.125 2.546)" gradientUnits="userSpaceOnUse"><stop class="vrnylccvf"/><stop offset="1" class="b442o21cz"/></radialGradient><radialGradient id="iRrohzc" cx="0" cy="0" r="1" gradientTransform="matrix(-.51053 .55695 -.77832 -.71345 15.434 3.39)" gradientUnits="userSpaceOnUse"><stop class="di6ktzbyk"/><stop offset="1" class="ejv935bph"/></radialGradient><radialGradient id="ipK38ad" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 7.778 3.99)scale(.88612 1.92808)" gradientUnits="userSpaceOnUse"><stop class="kdig6mnba"/><stop offset="1" class="him6rrbhz"/></radialGradient><radialGradient id="iG1Unmd" cx="0" cy="0" r="1" gradientTransform="rotate(156.949 7.412 5.122)scale(1.58043 2.51811)" gradientUnits="userSpaceOnUse"><stop class="c2fnpwywz"/><stop offset="1" class="c5g3vhi-m"/></radialGradient><radialGradient id="iBifC1c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .55552 -.42115 0 19.7 14.031)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="jove3dblx"/><stop offset="1" class="azrq8dbhb"/></radialGradient><radialGradient id="ikT3wpb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65625 1.65625 -1.54687 -1.54687 6.336 18.368)" gradientUnits="userSpaceOnUse"><stop class="mdx4akbxm"/><stop offset="1" class="t5qac2c1p"/></radialGradient><radialGradient id="ipd3rHo" cx="0" cy="0" r="1" gradientTransform="rotate(-174.823 3.309 9.547)scale(3.29739 3.69421)" gradientUnits="userSpaceOnUse"><stop offset=".439" class="mneu5xbew"/><stop offset=".947" class="fqax45bnt"/></radialGradient><radialGradient id="ieUwNdb" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 3.98763 -3.995 -.4383 5.462 18.087)" gradientUnits="userSpaceOnUse"><stop offset=".682" class="w7i-07blq"/><stop offset="1" class="o27_2ebdq"/></radialGradient><radialGradient id="iWmx2lc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34374 .78906 -.8071 -1.37445 6.282 18.844)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="rx_o_e39d"/><stop offset="1" class="ancrqsbmw"/></radialGradient><radialGradient id="ifKQLew" cx="0" cy="0" r="1" gradientTransform="matrix(.93752 -4.625 2.23622 .4533 11.556 25.118)" gradientUnits="userSpaceOnUse"><stop offset=".131" class="caco6ntri"/><stop offset="1" class="dgkitw09n"/></radialGradient><radialGradient id="iUeJ2Sb" cx="0" cy="0" r="1" gradientTransform="matrix(3.8125 -.34375 .46441 5.15075 9.868 22.712)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="t469b3jak"/><stop offset="1" class="qvoq5opiz"/></radialGradient><radialGradient id="iLF0nzb" cx="0" cy="0" r="1" gradientTransform="matrix(1.34136 3.28833 -5.45057 2.22337 6.741 26.606)" gradientUnits="userSpaceOnUse"><stop class="b1kvifv3j"/><stop offset="1" class="w__bqyylv"/></radialGradient><radialGradient id="iYUXpwc" cx="0" cy="0" r="1" gradientTransform="matrix(-.30078 .14845 -.19933 -.40386 10.865 26.565)" gradientUnits="userSpaceOnUse"><stop class="jfk78yx3r"/><stop offset="1" class="v_thlccbr"/></radialGradient><radialGradient id="iLV9ctc" cx="0" cy="0" r="1" gradientTransform="rotate(52.306 -21.855 22.55)scale(.76023 .57466)" gradientUnits="userSpaceOnUse"><stop class="jfk78yx3r"/><stop offset="1" class="v_thlccbr"/></radialGradient><radialGradient id="iVuFPpe" cx="0" cy="0" r="1" gradientTransform="rotate(153.3 8.342 12.627)scale(2.99172 1.46479)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="gckwtd8pq"/><stop offset="1" class="sg_-x3gmw"/></radialGradient><radialGradient id="ivkbt6S" cx="0" cy="0" r="1" gradientTransform="rotate(153.02 9.53 12.33)scale(1.92866 1.03496)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="pa6b3tb0c"/><stop offset="1" class="sdljx8amv"/></radialGradient><radialGradient id="ijJ6cKc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21874 .66407 -.44091 -.8092 23.173 18.116)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="don2uv-3m"/><stop offset="1" class="gpus1rbiy"/></radialGradient><radialGradient id="igATwqb" cx="0" cy="0" r="1" gradientTransform="rotate(112.416 5.878 17.729)scale(2.70434 1.05462)" gradientUnits="userSpaceOnUse"><stop offset=".566" class="n30gi-53g"/><stop offset="1" class="tt7xwipig"/></radialGradient><radialGradient id="is0WZfd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5 2.10937 -4.01056 -4.75325 19.634 19.837)" gradientUnits="userSpaceOnUse"><stop offset=".379" class="o7o4d8pps"/><stop offset=".92" class="j1n_ptbit"/></radialGradient><radialGradient id="ijCvQjy" cx="0" cy="0" r="1" gradientTransform="matrix(1.92188 1.03124 -1.60806 2.99689 16.696 19.149)" gradientUnits="userSpaceOnUse"><stop offset=".429" class="eaj548bgj"/><stop offset="1" class="cxprecb8d"/></radialGradient><radialGradient id="iqzarsk" cx="0" cy="0" r="1" gradientTransform="matrix(-.87818 .60937 -1.28653 -1.85405 19.918 18.758)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="bnpz8rbzn"/><stop offset="1" class="awgn1c4se"/></radialGradient><radialGradient id="icubEce" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 -3.875 4.85233 .35219 16.493 20.93)" gradientUnits="userSpaceOnUse"><stop class="c-qpqdbmc"/><stop offset="1" class="cy6exab_x"/></radialGradient><radialGradient id="i6Gutbe" cx="0" cy="0" r="1" gradientTransform="rotate(-75.406 21.683 2.268)scale(3.74586 2.0917)" gradientUnits="userSpaceOnUse"><stop class="sn3dy7bnn"/><stop offset="1" class="qu4z4jkud"/></radialGradient><radialGradient id="ijdo7Sd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.89062 -2.42602 0 16.93 16.852)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="u_3e452pz"/><stop offset="1" class="t5f4fqbxv"/></radialGradient><radialGradient id="iuKSyQd" cx="0" cy="0" r="1" gradientTransform="rotate(159.963 11.46 11.543)scale(2.82739 3.3966)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="uwn_p0-dn"/><stop offset="1" class="sa6pubcic"/></radialGradient><radialGradient id="ihRkukc" cx="0" cy="0" r="1" gradientTransform="matrix(3.40625 -1.28125 .6632 1.76315 6.712 13.93)" gradientUnits="userSpaceOnUse"><stop class="idtxb7bhf"/><stop offset="1" class="fl8n3u57c"/></radialGradient><radialGradient id="iK1dmYb" cx="0" cy="0" r="1" gradientTransform="matrix(2.34375 1.71875 -2.5451 3.4706 12.493 8.055)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="krme1767b"/><stop offset="1" class="nkhjpg89n"/></radialGradient><radialGradient id="iUHJpLd" cx="0" cy="0" r="1" gradientTransform="matrix(3.34375 -1 4.7268 15.80522 13.295 9.94)" gradientUnits="userSpaceOnUse"><stop offset=".67" class="zxq4xrt3q"/><stop offset="1" class="suc174tfe"/></radialGradient><radialGradient id="i4Y3dQd" cx="0" cy="0" r="1" gradientTransform="rotate(154.153 1.219 7.579)scale(1.51176 .82196)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="bq_62abtc"/><stop offset="1" class="uwcvcu_5g"/></radialGradient><radialGradient id="iiAKlHe" cx="0" cy="0" r="1" gradientTransform="rotate(149.949 .802 7.932)scale(1.74533 1.04837)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="bq_62abtc"/><stop offset="1" class="uwcvcu_5g"/></radialGradient><radialGradient id="iEW2KXc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49195 .93111 -.57955 -.92863 5.337 14.936)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="bq_62abtc"/><stop offset="1" class="uwcvcu_5g"/></radialGradient><radialGradient id="ieJiSGR" cx="0" cy="0" r="1" gradientTransform="rotate(149.08 .7 8.373)scale(1.53562 .93807)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="bq_62abtc"/><stop offset="1" class="uwcvcu_5g"/></radialGradient><radialGradient id="iSBOL3v" cx="0" cy="0" r="1" gradientTransform="rotate(129.668 -.122 8.925)scale(1.13713 .21244)" gradientUnits="userSpaceOnUse"><stop class="tjlv9x_9r"/><stop offset="1" class="z13dp2ohj"/></radialGradient><radialGradient id="iykYkLF" cx="0" cy="0" r="1" gradientTransform="rotate(106.912 4.94 9.223)scale(3.20093 4.86981)" gradientUnits="userSpaceOnUse"><stop class="env4r_bwx"/><stop offset="1" class="spg8_pgop"/></radialGradient><radialGradient id="i1bmqCd" cx="0" cy="0" r="1" gradientTransform="matrix(2.53394 .29688 -.19207 1.63939 5.897 13.227)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="k1ssgpxxp"/><stop offset="1" class="dcaablbea"/></radialGradient><radialGradient id="iOJ29Xd" cx="0" cy="0" r="1" gradientTransform="rotate(-50.981 21.25 -14.134)scale(2.33289 4.31503)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="ks47q0bjb"/><stop offset="1" class="ep0hblblj"/></radialGradient><radialGradient id="itEhSzd" cx="0" cy="0" r="1" gradientTransform="matrix(1.1487 -.52213 .6375 1.4025 14.76 6.244)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="iKvdW0d" cx="0" cy="0" r="1" gradientTransform="matrix(.46025 .1315 -.06914 .24197 15.233 5.22)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="i53sVud" cx="0" cy="0" r="1" gradientTransform="matrix(.56468 -.20885 .20885 .56468 15.016 6.15)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="iZK3csb" cx="0" cy="0" r="1" gradientTransform="matrix(-.56158 0 0 -.53719 10.742 6.041)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="inlgawb" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 6.472 4.456)scale(3.30514 4.42387)" gradientUnits="userSpaceOnUse"><stop class="uy3z2gbbp"/><stop offset="1" class="gvh2bspmv"/></radialGradient><radialGradient id="iI3i2nd" cx="0" cy="0" r="1" gradientTransform="matrix(-.97364 .515 -.43693 -.82606 13.773 6.114)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="itPRvhe" cx="0" cy="0" r="1" gradientTransform="matrix(.38624 -1.86682 2.36865 .49007 11.89 8.923)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="iGQkrzb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.4324 -4.65282 0 12.896 5.66)" gradientUnits="userSpaceOnUse"><stop offset=".684" class="sgt5sn5oc"/><stop offset="1" class="gxm-dc6uw"/></radialGradient><radialGradient id="i48b0Gd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.64548 .3558 -.61258 -4.55471 13.19 6.87)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="ivOvkce" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.53108 .76349 0 13.958 5.6)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="mt3h7fbpd"/><stop offset="1" class="wcr1klbjh"/></radialGradient><radialGradient id="itYgifd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.62764 .71932 0 12.01 5.64)" gradientUnits="userSpaceOnUse"><stop class="r-jog4w_t"/><stop offset="1" class="xjkdvxqyn"/></radialGradient><radialGradient id="iLXb9Sd" cx="0" cy="0" r="1" gradientTransform="matrix(-.62162 0 0 -2.04638 15.248 6.286)" gradientUnits="userSpaceOnUse"><stop class="yhs2bn2id"/><stop offset="1" class="g1fw3-bff"/></radialGradient><radialGradient id="iiOdENl" cx="0" cy="0" r="1" gradientTransform="matrix(.5336 1.94695 -4.02327 1.10267 11.742 3.252)" gradientUnits="userSpaceOnUse"><stop class="mih5kfbap"/><stop offset="1" class="kqfxh5bnm"/></radialGradient><radialGradient id="ia3kGxb" cx="0" cy="0" r="1" gradientTransform="matrix(-.32188 -1.13055 .64692 -.18418 13.258 6.622)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="i9muZVd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .374 -.59489 0 13.903 5.765)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="izZiv6d" cx="0" cy="0" r="1" gradientTransform="matrix(-.10691 -.13776 .18967 -.14719 13.798 5.803)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ipmQK5h" cx="0" cy="0" r="1" gradientTransform="matrix(0 .374 -.5949 0 11.889 5.765)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iCXplLc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00357 -.22775 .27377 -.00429 11.757 5.866)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iGWD65c" cx="0" cy="0" r="1" gradientTransform="rotate(54.19 1.988 11.495)scale(1.52615 3.03245)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="hi5yi9bqv"/><stop offset="1" class="d8y_5zbge"/></radialGradient><radialGradient id="iBCNJrc" cx="0" cy="0" r="1" gradientTransform="matrix(-.8664 1.14483 -.89784 -.67948 11.643 3.266)" gradientUnits="userSpaceOnUse"><stop class="g6mu4o3fz"/><stop offset="1" class="dx30lgbdy"/></radialGradient><radialGradient id="iluwzQb" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 6.14 5.523)scale(2.24884 3.19775)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="iz4jcxg0j"/><stop offset="1" class="qflnpfbur"/></radialGradient><radialGradient id="iwBJQvb" cx="0" cy="0" r="1" gradientTransform="rotate(104.957 5.859 6.824)scale(1.53203 2.73472)" gradientUnits="userSpaceOnUse"><stop class="mv8kv7beo"/><stop offset="1" class="g_ulzrbqz"/></radialGradient><radialGradient id="ixAJQqe" cx="0" cy="0" r="1" gradientTransform="rotate(-119.068 8.348 -1.245)scale(3.32762 2.97869)" gradientUnits="userSpaceOnUse"><stop offset=".891" class="w58maet4h"/><stop offset=".979" class="drxq29wnr"/></radialGradient><filter id="imlGAOe" width="7.181" height="7.681" x="9.431" y="1.355" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.698039 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23233"/></filter><filter id="iBbGMtd" width="7.486" height="8.65" x="14.87" y="7.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.447059 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23233"/></filter><filter id="iBBT3ud" width="5.439" height="5.49" x="2.462" y="16.583" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.223529 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23233"/></filter><filter id="iFklhFe" width="6.264" height="4.296" x="4.74" y="25.698" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.427451 0 0 0 0 0.341176 0 0 0 0 0.623529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23233"/></filter><filter id="i0ClwLb" width="5.105" height="3.176" x="4.74" y="26.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.564706 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23233"/></filter><filter id="iyfF6de" width="7.339" height="5.547" x="11.424" y="16.852" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23233"/></filter><filter id="iEMWerb" width="5.437" height="5.553" x="22.676" y="16.232" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.427451 0 0 0 0 0.286275 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23233"/></filter><filter id="iDRHm1d" width="2.689" height="5.353" x="25.224" y="16.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.92549 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23233"/></filter><filter id="inwGsEb" width="8.098" height="6.294" x="5.657" y="8.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.466667 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23233"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.364706 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23233" result="effect2_innerShadow_3987_23233"/></filter><filter id="iw60Cac" width="8.236" height="9.786" x="11.582" y="7.285" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.2"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23233"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.372549 0 0 0 0 0.262745 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23233" result="effect2_innerShadow_3987_23233"/></filter><filter id="iQCRose" width="2.625" height="5.367" x="19.763" y="9.308" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23233" stdDeviation=".25"/></filter><filter id="igPvCbc" width="3.404" height="3.248" x="18.396" y="8.305" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.760784 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23233"/></filter><filter id="iA4fWjc" width="1.635" height="1.735" x="9.991" y="5.298" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23233"/></filter><filter id="iN1EuQb" width="1.485" height="1.735" x="14.382" y="5.048" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23233"/></filter><filter id="ix4IPwT" width="1.991" height="1.991" x="14.128" y="5.045" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23233" stdDeviation=".25"/></filter><filter id="iXZ87me" width="1.791" height="1.791" x="9.847" y="5.145" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23233" stdDeviation=".2"/></filter><filter id="i7kuygU" width="4.703" height="5.12" x="10.545" y="3.776" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23233"/></filter><filter id="iQZ9P9d" width="1.866" height="2.238" x="11.888" y="5.308" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23233" stdDeviation=".25"/></filter><filter id="iYtlzfd" width="1.166" height="1.538" x="12.313" y="5.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23233" stdDeviation=".075"/></filter><filter id="iNoGiOb" width="1.924" height=".92" x="11.934" y="7.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23233" stdDeviation=".05"/></filter><filter id="iwMEVxe" width="1.493" height=".593" x="13.223" y="5.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23233"/></filter><filter id="iktw7Xb" width="1.493" height=".593" x="11.076" y="5.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23233"/></filter><filter id="i0yLwhb" width="1.24" height=".611" x="11.139" y="4.628" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23233"/></filter><filter id="iwGxVwb" width="1.24" height=".611" x="13.639" y="4.628" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23233"/></filter><filter id="iYFIZ3A" width=".471" height=".429" x="13.511" y="5.509" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23233" stdDeviation=".05"/></filter><filter id="icVTBnb" width=".626" height=".637" x="13.844" y="5.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23233" stdDeviation=".1"/></filter><filter id="iG6LCgZ" width=".67" height=".695" x="11.794" y="5.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23233" stdDeviation=".1"/></filter><filter id="iwVkMhd" width=".529" height=".433" x="11.499" y="5.505" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23233" stdDeviation=".05"/></filter><filter id="iOv8ESb" width="1.066" height=".474" x="13.641" y="4.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23233" stdDeviation=".05"/></filter><filter id="iEPqLre" width="1.066" height=".474" x="11.126" y="4.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23233" stdDeviation=".05"/></filter><filter id="ikosrEe" width="2.017" height="2.461" x="9.988" y="2.779" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23233" stdDeviation=".125"/></filter><filter id="ih2syAc" width="4.183" height="2.737" x="11.331" y="2.28" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23233" stdDeviation=".075"/></filter><filter id="iqU1aUE" width="1.556" height=".709" x="11.037" y="3.768" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.345098 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23233"/></filter><linearGradient id="iswxPLd" x1="15.062" x2="11.922" y1="2.832" y2="8.649" gradientUnits="userSpaceOnUse"><stop class="p6otu2-6b"/><stop offset="1" class="q5mih6mme"/></linearGradient><linearGradient id="inFRzLc" x1="4.743" x2="6.868" y1="18.993" y2="21.118" gradientUnits="userSpaceOnUse"><stop class="v616eizae"/><stop offset=".904" class="zbj0d-fph"/></linearGradient><linearGradient id="iP5V8Vd" x1="11.118" x2="8.993" y1="26.305" y2="25.555" gradientUnits="userSpaceOnUse"><stop class="g7n19jw2p"/><stop offset="1" class="lw0wsfo7o"/></linearGradient><linearGradient id="iqsv5Db" x1="8.915" x2="10.134" y1="25.305" y2="25.769" gradientUnits="userSpaceOnUse"><stop class="ykf__gbvs"/><stop offset="1" class="jpzj4ccfh"/></linearGradient><linearGradient id="iforYlw" x1="5.181" x2="9.845" y1="27.212" y2="29.743" gradientUnits="userSpaceOnUse"><stop class="rtyid72og"/><stop offset="1" class="bcnephb9f"/></linearGradient><linearGradient id="inONwub" x1="7.524" x2="7.466" y1="28.141" y2="28.247" gradientUnits="userSpaceOnUse"><stop offset=".401" class="poy_ydb2w"/><stop offset="1" class="f_xo_r1_u"/></linearGradient><linearGradient id="iKFMiMe" x1="21.97" x2="21.54" y1="21.133" y2="20.36" gradientUnits="userSpaceOnUse"><stop class="s6dne5bmb"/><stop offset="1" class="mur73_bqp"/></linearGradient><linearGradient id="iXXJehd" x1="23.368" x2="23.009" y1="20.415" y2="19.68" gradientUnits="userSpaceOnUse"><stop class="wh6te8bft"/><stop offset="1" class="yodkvfdyw"/></linearGradient><linearGradient id="iC1Fxvb" x1="26.313" x2="26.114" y1="18.844" y2="18.93" gradientUnits="userSpaceOnUse"><stop offset=".244" class="ivbdbpjuw"/><stop offset="1" class="zovioqy4e"/></linearGradient><linearGradient id="iaRXfSt" x1="27.532" x2="25.439" y1="21.155" y2="16.279" gradientUnits="userSpaceOnUse"><stop class="rtyid72og"/><stop offset="1" class="bcnephb9f"/></linearGradient><linearGradient id="iXLciIc" x1="26.269" x2="26.38" y1="18.973" y2="18.927" gradientUnits="userSpaceOnUse"><stop offset=".401" class="vvs_3yeki"/><stop offset="1" class="waplrebxe"/></linearGradient><linearGradient id="ilvXOyx" x1="18.384" x2="14.604" y1="15.171" y2="16.378" gradientUnits="userSpaceOnUse"><stop offset=".207" class="uov-5vb3w"/><stop offset="1" class="mzo6olgul"/></linearGradient><linearGradient id="irN4kmc" x1="9.991" x2="11.357" y1="6.081" y2="6.081" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="iHrHYCe" x1="12.413" x2="12.808" y1="6.63" y2="6.678" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="iCx9zob" x1="12.896" x2="12.896" y1="7.024" y2="6.742" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="iRnfajo" x1="12.56" x2="12.768" y1="7.706" y2="7.303" gradientUnits="userSpaceOnUse"><stop class="hvrv4iryz"/><stop offset="1" class="u1r8ksb5m"/></linearGradient><linearGradient id="i5Ri29d" x1="14.262" x2="14.117" y1="5.79" y2="5.879" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ih1ETXb" x1="12.232" x2="12.088" y1="5.79" y2="5.879" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-bouncing-ball-medium-light" /></template>
<style>
.acxmtrlex {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M15.124 6.537a.496.496 0 1 0 0-.992a.496.496 0 0 0 0 .992");
}

.ah2pisbqb {
  d: path("M9.794 29.424a.1.1 0 0 1 .043.126l-.04.097a.4.4 0 0 1-.564.197l-4.34-2.418a.3.3 0 0 1-.106-.425l.106-.163a.15.15 0 0 1 .2-.05z");
}

.al5lvkbaq {
  d: path("m11.432 25.156l-.853 2.118l-1.977-.969c.176-.463.47-1.25.755-2.041z");
}

.ancrqsbmw {
  stop-color: var(--svg-color--4c3945, #4C3945);
}

.aps1jhbfc {
  stop-color: var(--svg-color--b47860, #B47860);
}

.aso-vybjw {
  stop-color: var(--svg-color--d59566, #D59566);
}

.asssleb6w {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M10.742 6.537a.496.496 0 1 0 0-.992a.496.496 0 0 0 0 .992");
}

.awgn1c4se {
  stop-color: var(--svg-color--9e99a0, #9E99A0);
  stop-opacity: 0;
}

.azrq8dbhb {
  stop-color: var(--svg-color--b86660, #B86660);
}

.b1kvifv3j {
  stop-color: var(--svg-color--8668c7, #8668C7);
}

.b442o21cz {
  stop-color: var(--svg-color--dcc893, #DCC893);
  stop-opacity: 0;
}

.bcnephb9f {
  stop-color: var(--svg-color--d4c1e8, #D4C1E8);
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.bjv4rmbti {
  d: path("M11.888 5.545a.41.41 0 0 0-.397.52h.795a.414.414 0 0 0-.398-.52");
}

.bnpz8rbzn {
  stop-color: var(--svg-color--9e99a0, #9E99A0);
}

.bq_62abtc {
  stop-color: var(--svg-color--c9786e, #C9786E);
}

.bqbx36b8n {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.896 7.385a1.4 1.4 0 0 1-.656-.16c-.065-.033-.135.042-.094.102a.892.892 0 0 0 1.5 0c.04-.063-.029-.135-.094-.101a1.4 1.4 0 0 1-.656.159Z");
}

.bso4iybss {
  d: path("M13.874 5.632c.029.04-.032.087-.102.14c-.07.052-.121.088-.15.05c-.03-.04.003-.114.072-.166c.07-.052.15-.063.18-.024");
}

.c-qpqdbmc {
  stop-color: var(--svg-color--806d93, #806D93);
}

.c2fnpwywz {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
}

.c5g3vhi-m {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
  stop-opacity: 0;
}

.c7tegqbne {
  d: path("m11 20.61l.673-.75l2.336 1.86c-.07.046-.328.207-.797.476c-.644.412-1.029 1.088-1.14 1.375l-1.493 3.703l-1.977-.969c.326-.86 1.06-2.837 1.391-3.875s.81-1.645 1.008-1.82");
}

.caco6ntri {
  stop-color: var(--svg-color--edb29a, #EDB29A);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cqr5aro8f {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M13.874 5.632c.029.04-.032.087-.102.14c-.07.052-.121.088-.15.05c-.03-.04.003-.114.072-.166c.07-.052.15-.063.18-.024");
}

.cre_5tbhq {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
  stop-opacity: 0;
}

.cxprecb8d {
  stop-color: var(--svg-color--93869f, #93869F);
  stop-opacity: 0;
}

.cy6exab_x {
  stop-color: var(--svg-color--806d93, #806D93);
  stop-opacity: 0;
}

.d8y_5zbge {
  stop-color: var(--svg-color--daa88f, #DAA88F);
}

.dcaablbea {
  stop-color: var(--svg-color--ddac86, #DDAC86);
  stop-opacity: 0;
}

.demh68bgv {
  fill: var(--svg-color--e8b491, #E8B491);
  fill-rule: evenodd;
  d: path("M5.23 14.111c-.306.178-.45.37-.473.426a.415.415 0 0 1-.768-.315c.12-.291.436-.603.824-.828c.407-.237.95-.414 1.58-.382a.415.415 0 1 1-.042.829a2.03 2.03 0 0 0-1.12.27");
}

.dgkitw09n {
  stop-color: var(--svg-color--c2886c, #C2886C);
}

.di6ktzbyk {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
}

.dl0oclbay {
  d: path("M10.734 6.784a.743.743 0 1 0 0-1.486a.743.743 0 0 0 0 1.486");
}

.don2uv-3m {
  stop-color: var(--svg-color--9c7f8c, #9C7F8C);
}

.drxq29wnr {
  stop-color: var(--svg-color--dac493, #DAC493);
}

.dvyniwihb {
  stop-color: var(--svg-color--c57f82, #C57F82);
}

.dx30lgbdy {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
  stop-opacity: 0;
}

.dy6986bug {
  fill-rule: evenodd;
  d: path("M6.293 14.785c-.79-.084-1.136.336-1.209.514a.415.415 0 0 1-.768-.315c.211-.515.904-1.148 2.065-1.025a.415.415 0 1 1-.088.825");
}

.dz7zwddgg {
  cx: 11.764px;
  cy: 5.721px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.18px;
  ry: 0.091px;
}

.e28we4bnz {
  d: path("M23.563 19.826v-.779a.27.27 0 0 0-.277-.292c-.162.01-.507-.056-.594-.395s.206-.574.363-.649l2.362-1.328a.4.4 0 0 1 .566.195l1.907 4.587a.3.3 0 0 1-.18.399l-.568.194a.53.53 0 0 1-.625-.246c-.766-1.312-1.607-1.506-2.042-1.52a1.4 1.4 0 0 0-.51.089c-.185.065-.402-.06-.402-.255");
}

.e2cbcwbro {
  width: 0.659px;
  height: 1.111px;
  x: 19.37px;
  y: 13.476px;
  rx: 0.33px;
}

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
}

.eaj548bgj {
  stop-color: var(--svg-color--695279, #695279);
}

.ejv935bph {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
  stop-opacity: 0;
}

.ek5bxabzl {
  d: path("M5.527 16.653c.013.613.238 1.167.598 1.588l.897-.892q.093.085.176.178l-.9.895a2.23 2.23 0 0 0 1.586.622q.014.123.017.25h-.065A2.48 2.48 0 0 1 6.12 18.6l-.777.772l1.754 1.914q-.088.087-.185.167l-1.746-1.905l-.77.765c.422.461.689 1.08.714 1.761a3 3 0 0 1-.25-.018a2.5 2.5 0 0 0-.64-1.567l-.877.872a3 3 0 0 1-.177-.177l.876-.87a2.23 2.23 0 0 0-1.556-.576a3 3 0 0 1-.024-.25l.091-.001c.638 0 1.22.245 1.666.65l.778-.773l-1.758-1.918q.088-.089.184-.17l1.751 1.912l.774-.77a2.77 2.77 0 0 1-.671-1.784q.127.005.25.02");
}

.env4r_bwx {
  stop-color: var(--svg-color--966bb1, #966BB1);
}

.ep0hblblj {
  stop-color: var(--svg-color--c1add1, #C1ADD1);
  stop-opacity: 0;
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.f_xo_r1_u {
  stop-color: var(--svg-color--e4d5e5, #E4D5E5);
  stop-opacity: 0;
}

.f513s74td {
  fill: var(--svg-color--9f6836, #9F6836);
  d: path("m11.328 5.22l-.002.002a.124.124 0 0 1-.127-.213h.002l.004-.003l.015-.009l.054-.027c.045-.021.11-.05.189-.074c.157-.05.376-.093.613-.05a.124.124 0 1 1-.043.243c-.184-.033-.36 0-.495.042a1.3 1.3 0 0 0-.2.084z");
}

.f7g2qnjfz {
  fill: var(--svg-color--9f97a6, #9F97A6);
  d: path("M12.593 4.477h-1.556c.214-.12.386-.305.48-.54l.04-.092a.124.124 0 0 1 .216-.024c.204.3.492.525.82.656");
}

.feam4fbza {
  fill: var(--svg-color--9f6836, #9F6836);
  fill-rule: evenodd;
  d: path("m14.618 5.01l-.063.106za.124.124 0 0 1-.127.213l-.002-.001l-.01-.006l-.042-.021a1 1 0 0 0-.158-.063a1.05 1.05 0 0 0-.495-.042a.124.124 0 0 1-.043-.244c.237-.042.456 0 .613.05a1.5 1.5 0 0 1 .258.11l.004.003z");
}

.fl8n3u57c {
  stop-color: var(--svg-color--c48b6f, #C48B6F);
}

.fqax45bnt {
  stop-color: var(--svg-color--bf5347, #BF5347);
}

.ft5dv1b6b {
  fill: none;
}

.g_ulzrbqz {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
  stop-opacity: 0;
}

.g1fw3-bff {
  stop-color: var(--svg-color--f4c099, #F4C099);
  stop-opacity: 0;
}

.g30_hrb9q {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M12.896 7.385a1.4 1.4 0 0 1-.656-.16c-.065-.033-.135.042-.094.102a.892.892 0 0 0 1.5 0c.04-.063-.029-.135-.094-.101a1.4 1.4 0 0 1-.656.159");
}

.g6mu4o3fz {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
}

.g7n19jw2p {
  stop-color: var(--svg-color--e2cded, #E2CDED);
}

.gckwtd8pq {
  stop-color: var(--svg-color--e3ab8f, #E3AB8F);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gop4tkdej {
  d: path("M12.264 5.909c0-.133-.108-.222-.137-.249l-.133.129l.082.166z");
}

.gpus1rbiy {
  stop-color: var(--svg-color--ccbdcf, #CCBDCF);
  stop-opacity: 0;
}

.gtp576ola {
  d: path("M11.884 8.917c.147.243.5.623 1.02.623c.886 0 1.253-.43 1.542-1.102c.124-.288.365-.789.438-.953c.695.105.89.273.89.273l.008.012c-.149.277-.4.781-.453.985c-.07.273-.238 1.05.25 1.687c.373.487.812.598 1.233.588c.48 1.403 1.533 4.46 1.99 5.701a.253.253 0 0 1-.238.34h-5.25a.57.57 0 0 1-.55-.391c-.423-1.315-.893-3.615-1.107-4.969c-.19-1.197.014-2.232.227-2.794");
}

.gvh2bspmv {
  stop-color: var(--svg-color--d39b88, #D39B88);
}

.gxm-dc6uw {
  stop-color: var(--svg-color--a46e69, #A46E69);
}

.hcuenbefp {
  stop-color: var(--svg-color--c7897d, #C7897D);
  stop-opacity: 0;
}

.hi5yi9bqv {
  stop-color: var(--svg-color--daa88f, #DAA88F);
  stop-opacity: 0;
}

.him6rrbhz {
  stop-color: var(--svg-color--fffabe, #FFFABE);
  stop-opacity: 0;
}

.hnazsfbsb {
  fill: var(--svg-color--e8b491, #E8B491);
  fill-rule: evenodd;
  d: path("M6.322 13.691c-.775-.132-1.17.09-1.3.29a.415.415 0 1 1-.696-.452c.391-.605 1.214-.813 2.135-.656a.415.415 0 0 1-.14.818");
}

.hvrv4iryz {
  stop-color: var(--svg-color--d8a29e, #D8A29E);
}

.hxuphr-8h {
  stop-color: var(--svg-color--cf987b, #CF987B);
}

.i21jitbel {
  d: path("M12.618 2.446c-.523-.116-1.083.44-1.137.634c.711 1.67 1.804 1.512 3.016 1.377c.726-.08.805.25.867.41c-.201-1.872-1.555-2.158-2.746-2.421");
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.idtxb7bhf {
  stop-color: var(--svg-color--dfa98a, #DFA98A);
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.ivbdbpjuw {
  stop-color: var(--svg-color--614a93, #614A93);
}

.iz4jcxg0j {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
  stop-opacity: 0;
}

.izewy3bwp {
  fill: var(--svg-color--ffc9a7, #FFC9A7);
  d: path("M11.657 11.712c-.238-1.5.143-2.745.383-3.125c.293-.607.987-.805 1.296-.829h2.438c.386.578.634 1.596.744 2.24c.034.204.078.404.145.6c.365 1.064 1.627 4.74 2.14 6.133a.253.253 0 0 1-.239.34h-5.25a.57.57 0 0 1-.55-.391c-.423-1.315-.893-3.615-1.107-4.969");
}

.j1n_ptbit {
  stop-color: var(--svg-color--7b5a93, #7B5A93);
}

.j2gnpuyah {
  d: path("m12.72 5.874l-.245.785a.25.25 0 0 0 .24.323h.363a.25.25 0 0 0 .24-.323l-.245-.785c-.053-.173-.298-.173-.353 0");
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.jfk78yx3r {
  stop-color: var(--svg-color--9a82d0, #9A82D0);
}

.jg8nvfbol {
  fill: var(--svg-color--e8e5eb, #E8E5EB);
  d: path("M19.324 8.31a.095.095 0 0 0-.107.03c-.44.551-.75 1.567-.821 2.057c.167.062.314.136.432.225c.418.266.704.576.875.93c.812-.548 1.637-.801 2.096-.855c-.34-.803-.92-1.49-1.734-2.009a4 4 0 0 0-.741-.377");
}

.jove3dblx {
  stop-color: var(--svg-color--c48770, #C48770);
}

.jpzj4ccfh {
  stop-color: var(--svg-color--c4b0ca, #C4B0CA);
  stop-opacity: 0;
}

.jv-6hac0r {
  d: path("M13.904 5.545a.41.41 0 0 1 .396.52h-.795a.413.413 0 0 1 .398-.52");
}

.k1ssgpxxp {
  stop-color: var(--svg-color--ddac86, #DDAC86);
}

.kdica8byl {
  d: path("M10.742 6.537a.496.496 0 1 0 0-.992a.496.496 0 0 0 0 .992");
}

.kdig6mnba {
  stop-color: var(--svg-color--fffabe, #FFFABE);
}

.km0jvbbqs {
  cx: 11.764px;
  cy: 5.721px;
  rx: 0.18px;
  ry: 0.091px;
}

.kqfxh5bnm {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
  stop-opacity: 0;
}

.krme1767b {
  stop-color: var(--svg-color--b56e59, #B56E59);
}

.krvd34mtu {
  stop-color: var(--svg-color--d59566, #D59566);
  stop-opacity: 0;
}

.ks47q0bjb {
  stop-color: var(--svg-color--9f6ea3, #9F6EA3);
}

.ktiqp3mew {
  d: path("M19.267 22.462c-.213.09-.352.069-.372.046l.754-2.93a.72.72 0 0 0 .555-.038l3.11-1.75l.726 2.144c-1.518.805-4.561 2.437-4.773 2.528");
}

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.liuw-nhbd {
  fill: var(--svg-color--83788b, #83788B);
  d: path("M12.962 17.462a4 4 0 0 1 .265-.61h5.149c.539 1.52-.652 2.926-1.2 3.238l-3.085 1.899c-.242.148-.512.238-.73.066c-.759-.531-1.555-1.508-1.844-2.008c-.232-.4.023-.74.18-.859c.827-.7 1.148-1.383 1.265-1.726");
}

.log-m9nxt {
  fill: var(--svg-color--e8b491, #E8B491);
  fill-rule: evenodd;
  d: path("M5.125 14.603c-.293.2-.45.423-.481.5a.415.415 0 1 1-.768-.314c.11-.27.397-.61.78-.871c.398-.271.941-.49 1.589-.457a.415.415 0 0 1-.042.83a1.74 1.74 0 0 0-1.078.312");
}

.lw0wsfo7o {
  stop-color: var(--svg-color--c5b1cb, #C5B1CB);
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.m-h0k-bsf {
  fill-rule: evenodd;
  d: path("m11.974 9.002l.053-.091l1.728 1.008l-.074.126c-.712 1.225-1.57 2.698-3.676 3.891c-.768.435-1.654.657-2.381.773c-.257.042-.503.07-.729.092c-.55.05-.994-.403-.988-.956l.01-1.024c.251.003.784.01 1.39-.086c.617-.1 1.238-.27 1.712-.539c1.633-.925 2.26-2 2.955-3.194");
}

.m-uhwp86n {
  d: path("M10.637 3.266c.287-.256.7-.258.932-.217l.186.596a.36.36 0 0 0-.313.108c-.209.774-.998.657-1.153 1.238c-.07-.689-.147-1.284.348-1.725");
}

.m526cvbra {
  d: path("m10.55 5.336l-.005-.141c.009-.438.265-.608.373-.664l.024-.01l.024-.01c.246-.112.445-.31.549-.569l.038-.09a.122.122 0 0 1 .213-.023c.33.485.885.772 1.471.772h1.486c.083 0 .5.04.525.615l-.055 1.418c-.057 1.294-1.067 2.162-2.3 2.162s-2.243-.868-2.3-2.162z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdx4akbxm {
  stop-color: var(--svg-color--ff8c60, #FF8C60);
}

.mih5kfbap {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
}

.mneu5xbew {
  stop-color: var(--svg-color--fa4e2e, #FA4E2E);
  stop-opacity: 0;
}

.mt3h7fbpd {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
}

.mur73_bqp {
  stop-color: var(--svg-color--d89d91, #D89D91);
  stop-opacity: 0;
}

.mv8kv7beo {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
}

.mvuactshi {
  stop-color: var(--svg-color--c49070, #C49070);
  stop-opacity: 0;
}

.mzo6olgul {
  stop-color: var(--svg-color--8568c5, #8568C5);
  stop-opacity: 0;
}

.n30gi-53g {
  stop-color: var(--svg-color--a471bc, #A471BC);
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.nkhjpg89n {
  stop-color: var(--svg-color--cd8f76, #CD8F76);
  stop-opacity: 0;
}

.nsr99pb0o {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m12.715 5.938l-.315.785a.25.25 0 0 0 .24.323h.363a.25.25 0 0 0 .24-.323l-.245-.785c-.053-.174-.228-.174-.283 0");
}

.o27_2ebdq {
  stop-color: var(--svg-color--d85b75, #D85B75);
}

.o7o4d8pps {
  stop-color: var(--svg-color--92869f, #92869F);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oo7nk3bzn {
  d: path("M10.548 5.458h.006l-.005-.122l-.004-.141c.009-.438.265-.608.373-.664l.024-.01l.024-.01c.246-.112.445-.31.549-.569l.038-.09a.122.122 0 0 1 .213-.023c.33.485.885.772 1.471.772h1.486c.083 0 .5.04.525.615l-.055 1.418c-.057 1.294-1.067 2.162-2.3 2.162s-2.243-.868-2.3-2.162z");
}

.oolpdvc_e {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M12.37 5.778c-.123-.215-.31-.385-.71-.385a.77.77 0 0 0-.495.17c-.124.1-.108.229-.012.277l.257.146c.3-.097.633-.11.96-.208");
}

.opsul3b2p {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.791 4.946c.15-.036.519-.018.766.159");
}

.otq0w83qz {
  d: path("M15.124 6.537a.496.496 0 1 0 0-.992a.496.496 0 0 0 0 .992");
}

.p1sg1mumi {
  stop-color: var(--svg-color--ffc3a8, #FFC3A8);
  stop-opacity: 0;
}

.p6otu2-6b {
  stop-color: var(--svg-color--ffffbe, #FFFFBE);
}

.pa6b3tb0c {
  stop-color: var(--svg-color--cfbedb, #CFBEDB);
}

.pdil1tsmk {
  d: path("M15.124 6.784a.743.743 0 1 0 0-1.486a.743.743 0 0 0 0 1.486");
}

.pid-4m06y {
  cx: 5.18px;
  cy: 19.353px;
  r: 2.721px;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.poy_ydb2w {
  stop-color: var(--svg-color--e4d5e5, #E4D5E5);
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.ptg5rr5de {
  fill: var(--svg-color--fac6a5, #FAC6A5);
  d: path("M20.857 14.175c.475-1.675-.198-3.354-.594-3.984l.782-.383c.906 1.672.953 2.773.734 3.617z");
}

.q5mih6mme {
  stop-color: var(--svg-color--e5ae90, #E5AE90);
}

.qflnpfbur {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
}

.qk3iylyni {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M13.423 5.778c.123-.215.309-.385.71-.385c.175 0 .345.048.495.17c.124.1.107.229.011.277l-.256.146c-.301-.097-.634-.11-.96-.208");
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qu4z4jkud {
  stop-color: var(--svg-color--9380a4, #9380A4);
  stop-opacity: 0;
}

.qvoq5opiz {
  stop-color: var(--svg-color--b37381, #B37381);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-jog4w_t {
  stop-color: var(--svg-color--c2847a, #C2847A);
}

.r6_hcsbxi {
  d: path("m9.12 25.796l.482.61a.27.27 0 0 0 .399.06c.12-.109.433-.272.71-.06c.279.213.195.579.118.735l-1.032 2.506a.4.4 0 0 1-.564.197l-4.34-2.418A.3.3 0 0 1 4.789 27l.326-.505a.53.53 0 0 1 .643-.194c1.414.556 2.194.187 2.545-.07a1.4 1.4 0 0 0 .345-.388c.104-.165.353-.202.473-.048");
}

.rbd89zfgs {
  fill-rule: evenodd;
  d: path("M6.322 13.691c-.775-.132-1.17.09-1.3.29a.415.415 0 1 1-.696-.452c.391-.605 1.214-.813 2.135-.656a.415.415 0 0 1-.14.818");
}

.rjxj417_v {
  stop-color: var(--svg-color--f9bfa4, #F9BFA4);
}

.rtyid72og {
  stop-color: var(--svg-color--d5c2e7, #D5C2E7);
}

.rx_o_e39d {
  stop-color: var(--svg-color--4d3a45, #4D3A45);
}

.s6dne5bmb {
  stop-color: var(--svg-color--ba7b8a, #BA7B8A);
}

.sa6pubcic {
  stop-color: var(--svg-color--8466c4, #8466C4);
}

.sdljx8amv {
  stop-color: var(--svg-color--c7b9c5, #C7B9C5);
}

.sg_-x3gmw {
  stop-color: var(--svg-color--ce9878, #CE9878);
}

.sgt5sn5oc {
  stop-color: var(--svg-color--bd8381, #BD8381);
  stop-opacity: 0;
}

.sn3dy7bnn {
  stop-color: var(--svg-color--9380a4, #9380A4);
}

.spg8_pgop {
  stop-color: var(--svg-color--966bb1, #966BB1);
  stop-opacity: 0;
}

.sqmgyf2vi {
  stop-color: var(--svg-color--c49070, #C49070);
}

.st-rm_qqx {
  fill-rule: evenodd;
  d: path("M5.23 14.111c-.306.178-.45.37-.473.426a.415.415 0 0 1-.768-.315c.12-.291.436-.603.824-.828c.407-.237.95-.414 1.58-.382a.415.415 0 1 1-.042.829a2.03 2.03 0 0 0-1.12.27");
}

.suc174tfe {
  stop-color: var(--svg-color--ebaf94, #EBAF94);
}

.t469b3jak {
  stop-color: var(--svg-color--b37381, #B37381);
  stop-opacity: 0;
}

.t5f4fqbxv {
  stop-color: var(--svg-color--84798d, #84798D);
  stop-opacity: 0;
}

.t5qac2c1p {
  stop-color: var(--svg-color--ff8c60, #FF8C60);
  stop-opacity: 0;
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
}

.t9az4wpbm {
  fill: var(--svg-color--000, #000);
  d: path("M13.668 5.957c0-.131.105-.236.236-.236a.235.235 0 0 1 .21.344h-.418a.2.2 0 0 1-.028-.108");
}

.ta36f8b7v {
  stop-color: var(--svg-color--c7897d, #C7897D);
}

.tjlv9x_9r {
  stop-color: var(--svg-color--f1bda3, #F1BDA3);
}

.tokrlwc9z {
  fill: var(--svg-color--000, #000);
  d: path("M12.124 5.957a.235.235 0 0 0-.236-.236a.235.235 0 0 0-.21.344h.418a.23.23 0 0 0 .028-.108");
}

.tt7xwipig {
  stop-color: var(--svg-color--a471bc, #A471BC);
  stop-opacity: 0;
}

.u_3e452pz {
  stop-color: var(--svg-color--918b96, #918B96);
}

.u1r8ksb5m {
  stop-color: var(--svg-color--d8a29e, #D8A29E);
  stop-opacity: 0;
}

.u1t7v_b3t {
  fill-rule: evenodd;
  d: path("M7.132 13.94a.415.415 0 0 1 .118.574a8 8 0 0 1-.913 1.131a.415.415 0 1 1-.602-.57l.005-.006c.16-.169.494-.522.817-1.012a.415.415 0 0 1 .575-.118");
}

.ub-9o4pik {
  d: path("M25.282 16.56a.1.1 0 0 1 .044-.125l.091-.052a.4.4 0 0 1 .566.195l1.907 4.587a.3.3 0 0 1-.18.399l-.184.063a.15.15 0 0 1-.187-.085z");
}

.ue-yx0baa {
  stop-color: var(--svg-color--c58e72, #C58E72);
  stop-opacity: 0;
}

.uov-5vb3w {
  stop-color: var(--svg-color--9782d0, #9782D0);
}

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.uv36sqbhc {
  d: path("M18.292 22.665c-1.2-.712-1.919-1.898-2.143-2.453l2.156-3.016c.378.41 1.05 1.396 1.46 2.022a.9.9 0 0 1 .148.584c-.12 1.06-.567 2.06-.923 2.676a.505.505 0 0 1-.698.187");
}

.uwcvcu_5g {
  stop-color: var(--svg-color--c9786e, #C9786E);
  stop-opacity: 0;
}

.uwn_p0-dn {
  stop-color: var(--svg-color--8366c4, #8366C4);
}

.uy3z2gbbp {
  stop-color: var(--svg-color--ffc59d, #FFC59D);
}

.v_thlccbr {
  stop-color: var(--svg-color--9a82d0, #9A82D0);
  stop-opacity: 0;
}

.v-9s4u7ch {
  stop-color: var(--svg-color--cf987b, #CF987B);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v616eizae {
  stop-color: var(--svg-color--f84c2c, #F84C2C);
}

.v6h8iny7i {
  fill: var(--svg-color--e8b491, #E8B491);
  fill-rule: evenodd;
  d: path("M6.293 14.785c-.79-.084-1.136.336-1.209.514a.415.415 0 0 1-.768-.315c.211-.515.904-1.148 2.065-1.025a.415.415 0 1 1-.088.825");
}

.vrnylccvf {
  stop-color: var(--svg-color--dcc893, #DCC893);
}

.vvs_3yeki {
  stop-color: var(--svg-color--bfa7d0, #BFA7D0);
}

.w__bqyylv {
  stop-color: var(--svg-color--8768cb, #8768CB);
}

.w-wyxqbcb {
  fill: var(--svg-color--edb791, #EDB791);
  d: path("M15.216 10.033q.558-.015 1.474.058c.827.065 1.691.195 2.138.53c.582.372.909.829 1.026 1.372c.133.614.023 1.14-.23 1.801l-.15.383c-.125.312-.24.6-.288.8c-.06.258.098.434.404.438c.055 0 .106.025.14.068a.4.4 0 0 0 .206.147c.082.021.14.016.22.01q.044-.006.1-.008c.047-.002.09.02.117.059a.33.33 0 0 0 .2.146a.45.45 0 0 0 .244-.017a.2.2 0 0 1 .172.021a.6.6 0 0 0 .205.086c.14.02.305-.04.367-.235c.035-.108.08-.297.121-.476c.098-.416.25-.821.25-1.254a4.95 4.95 0 0 0 .121-2.461c-.248-1.15-.915-2.129-1.988-2.812c-1.177-.75-3.758-.943-5.022-.903l-.173.004v2.25q.148 0 .346-.007");
}

.w58maet4h {
  stop-color: var(--svg-color--dac493, #DAC493);
  stop-opacity: 0;
}

.w7i-07blq {
  stop-color: var(--svg-color--f25c44, #F25C44);
  stop-opacity: 0;
}

.waplrebxe {
  stop-color: var(--svg-color--bfa7d0, #BFA7D0);
  stop-opacity: 0;
}

.wbh3f-b7s {
  d: path("M12.962 17.462a4 4 0 0 1 .265-.61h5.149c.539 1.52-.652 2.926-1.2 3.238l-3.085 1.899c-.242.148-.512.238-.73.066c-.759-.531-1.555-1.508-1.844-2.008c-.232-.4.023-.74.18-.859c.827-.7 1.148-1.383 1.265-1.726");
}

.wcr1klbjh {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
  stop-opacity: 0;
}

.wh6te8bft {
  stop-color: var(--svg-color--bb98d6, #BB98D6);
}

.whdc-5b4w {
  fill-rule: evenodd;
  d: path("M16.212 6.692a1.51 1.51 0 0 0 .026-1.261h.002a1.5 1.5 0 0 0-.13-.237v-.002a1.5 1.5 0 0 1-.243-.817V4.37c0-.84-.682-1.522-1.523-1.522a.25.25 0 0 1-.21-.108a1.526 1.526 0 0 0-2.476 0a.26.26 0 0 1-.21.108h-.039A1.523 1.523 0 0 0 9.926 4.37v.005c0 .29-.084.574-.243.817l-.001.002a1.52 1.52 0 0 0-.102 1.498a.24.24 0 0 1 0 .21a1.483 1.483 0 0 0 1.336 2.134h3.96a1.483 1.483 0 0 0 1.336-2.134a.24.24 0 0 1 0-.21m-5.658-1.234h-.005l.553 1.087c.057 1.294.561 0 1.794 0s1.77 1.44 1.827.147l.525-1.476c-.025-.574-.441-.615-.524-.615h-1.486a1.78 1.78 0 0 1-1.472-.772a.122.122 0 0 0-.213.024l-.038.089a1.06 1.06 0 0 1-.55.57l-.023.01l-.024.009c-.108.056-.364.226-.373.664l.004.14z");
}

.xcez8obke {
  fill: var(--svg-color--efb696, #EFB696);
  d: path("m12.72 5.874l-.245.785a.25.25 0 0 0 .24.323h.363a.25.25 0 0 0 .24-.323l-.245-.785c-.053-.173-.298-.173-.353 0");
}

.xjkdvxqyn {
  stop-color: var(--svg-color--c2847a, #C2847A);
  stop-opacity: 0;
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.xnrju8bbx {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.793 5.42a.645.645 0 0 0-.626.489c-.02.08.042.157.124.157h1.03c.065 0 .118-.06.104-.126a.65.65 0 0 0-.632-.52");
}

.xpipdtb9t {
  fill: var(--svg-color--876cc6, #876CC6);
  d: path("M11.884 8.917c.147.243.5.623 1.02.623c.886 0 1.253-.43 1.542-1.102c.124-.288.365-.789.438-.953c.695.105.89.273.89.273l.008.012c-.149.277-.4.781-.453.985c-.07.273-.238 1.05.25 1.687c.373.487.812.598 1.233.588c.48 1.403 1.533 4.46 1.99 5.701a.253.253 0 0 1-.238.34h-5.25a.57.57 0 0 1-.55-.391c-.423-1.315-.893-3.615-1.107-4.969c-.19-1.197.014-2.232.227-2.794");
}

.y1djx2bua {
  d: path("M19.324 8.31a.095.095 0 0 0-.107.03c-.44.551-.75 1.567-.821 2.057c.167.062.314.136.432.225c.418.266.704.576.875.93c.812-.548 1.637-.801 2.096-.855c-.34-.803-.92-1.49-1.734-2.009a4 4 0 0 0-.741-.377");
}

.y3287vlxz {
  d: path("M11.657 11.712c-.238-1.5.143-2.745.383-3.125c.293-.607.987-.805 1.296-.829h2.438c.386.578.634 1.596.744 2.24c.034.204.078.404.145.6c.365 1.064 1.627 4.74 2.14 6.133a.253.253 0 0 1-.239.34h-5.25a.57.57 0 0 1-.55-.391c-.423-1.315-.893-3.615-1.107-4.969");
}

.y74gd5bcp {
  fill: var(--svg-color--92869e, #92869E);
  d: path("M18.292 22.665c-1.2-.712-1.919-1.898-2.143-2.453l2.156-3.016c.378.41 1.05 1.396 1.46 2.022a.9.9 0 0 1 .148.584c-.12 1.06-.567 2.06-.923 2.676a.505.505 0 0 1-.698.187");
}

.ybvptdnhb {
  stop-color: var(--svg-color--c58e72, #C58E72);
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
}

.yhs2bn2id {
  stop-color: var(--svg-color--f4c099, #F4C099);
}

.ykf__gbvs {
  stop-color: var(--svg-color--a38f93, #A38F93);
}

.yodkvfdyw {
  stop-color: var(--svg-color--bb98d6, #BB98D6);
  stop-opacity: 0;
}

.yxnqo2bds {
  fill-rule: evenodd;
  d: path("M5.125 14.603c-.293.2-.45.423-.481.5a.415.415 0 1 1-.768-.314c.11-.27.397-.61.78-.871c.398-.271.941-.49 1.589-.457a.415.415 0 0 1-.042.83a1.74 1.74 0 0 0-1.078.312");
}

.z13dp2ohj {
  stop-color: var(--svg-color--e1ac8b, #E1AC8B);
}

.z7rtwjbyn {
  d: path("M14.27 5.903a.4.4 0 0 0-.106-.214l-.12.132l.054.105z");
}

.zb4vi2bec {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.042 4.946a1.1 1.1 0 0 0-.766.159");
}

.zbj0d-fph {
  stop-color: var(--svg-color--ff7937, #FF7937);
}

.ziv54kk1v {
  d: path("m22.282 20.87l.03-.016c.636-.34 1.256-.67 1.728-.92l-.727-2.144l-2.087 1.174z");
}

.zovioqy4e {
  stop-color: var(--svg-color--614a93, #614A93);
  stop-opacity: 0;
}

.zxq4xrt3q {
  stop-color: var(--svg-color--ebaf94, #EBAF94);
  stop-opacity: 0;
}

.zzb5anb_b {
  fill: var(--svg-color--fff, #fff);
  d: path("M14 5.42c.301 0 .556.208.625.489a.126.126 0 0 1-.124.157h-1.03a.106.106 0 0 1-.104-.126a.645.645 0 0 1 .633-.52");
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
