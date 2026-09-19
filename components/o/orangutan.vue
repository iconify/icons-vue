<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="gr2e7bywt"/><path fill="url(#iWSSExd)" class="gfypu3b_p"/><path fill="url(#iGKVmke)" class="gfypu3b_p"/><path fill="url(#ioVpnte)" class="xk6_c3zqa"/><path fill="url(#i74v5xW)" class="wer2ym_va"/><g filter="url(#iJdYbXd)"><path class="wnm6yvi7y"/></g><g filter="url(#iSD0Htc)"><path class="bwgmbd-bx"/></g><path fill="url(#iDI97zb)" class="x4-n5dbmw"/><path fill="url(#iThWNOe)" class="x4-n5dbmw"/><path fill="url(#iv07vyb)" class="x4-n5dbmw"/><path fill="url(#iWcxKJS)" class="x4-n5dbmw"/><g filter="url(#iqWy8yc)"><circle class="biivzhtww"/></g><path fill="url(#iIE1s5d)" class="erm4t9r7t"/><path fill="url(#iy0cNdc)" class="erm4t9r7t"/><path fill="url(#iTvDSZK)" class="erm4t9r7t"/><path fill="url(#i7AYAQb)" clip-rule="evenodd" class="h060x4brd"/><path fill="url(#iEjLGvd)" clip-rule="evenodd" class="h060x4brd"/><path fill="url(#igzCpKd)" clip-rule="evenodd" class="h060x4brd"/><path fill="url(#iLwt9od)" clip-rule="evenodd" class="h060x4brd"/><path fill="url(#iJxJfke)" class="ogrs9bbhe"/><path fill="url(#iZsdPTb)" class="ogrs9bbhe"/><path fill="url(#iCRqyLb)" class="ogrs9bbhe"/><path fill="url(#iXFzXIe)" class="fmvra1brm"/><path fill="url(#iod8plc)" class="fmvra1brm"/><path fill="url(#iUxF1wp)" class="fmvra1brm"/><path fill="url(#iNjvS7c)" class="sc6kk-2pn"/><path fill="url(#iDZrZos)" class="sc6kk-2pn"/><path fill="url(#iVOitqb)" class="sc6kk-2pn"/><g filter="url(#iewrkMe)"><path fill="url(#i0BH2EC)" class="mrdsf44xp"/><path fill="url(#iVR7l7d)" class="mrdsf44xp"/><path fill="url(#iNYxKuc)" class="mrdsf44xp"/><path fill="url(#iZuiNkb)" class="mrdsf44xp"/><path fill="url(#itL7Gkc)" class="mrdsf44xp"/></g><path fill="url(#i9MqFSb)" clip-rule="evenodd" class="i8cm5uskj"/><path fill="url(#ikGPtLe)" clip-rule="evenodd" class="i8cm5uskj"/><path fill="url(#itIOphT)" clip-rule="evenodd" class="i8cm5uskj"/><path fill="url(#ic4UUBe)" clip-rule="evenodd" class="i8cm5uskj"/><path fill="url(#i01svId)" class="y_h1t_b9h"/><path fill="url(#iloLJVd)" class="y_h1t_b9h"/><path fill="url(#i1aVYGe)" class="y_h1t_b9h"/><path fill="url(#ix6EKdb)" class="y_h1t_b9h"/><path fill="url(#iDaD0pc)" class="nenme4bly"/><path fill="url(#iHoBVXq)" class="nenme4bly"/><path fill="url(#iirNGse)" class="nenme4bly"/><path fill="url(#iIlhVsi)" class="fr9nhqbin"/><path fill="url(#ihroxTd)" class="fr9nhqbin"/><path fill="url(#iOmHQDN)" class="fr9nhqbin"/><path fill="url(#idZAV4d)" class="isgrikb0u"/><path fill="url(#itfPv9b)" class="isgrikb0u"/><path fill="url(#iieJSsc)" class="isgrikb0u"/><g filter="url(#iA4P4uc)"><path stroke="url(#iSDE2Ec)" class="ds_nv9bxv"/></g><path fill="url(#iWqjTXd)" class="m0q9s4bvb"/><path fill="url(#iAodz4b)" class="m0q9s4bvb"/><path fill="url(#ivw7vee)" class="g173qtpqz"/><path fill="url(#iunIOtb)" class="g173qtpqz"/><path fill="url(#iMdJw2D)" class="wzx_ohz0x"/><path fill="url(#ibVzuIb)" class="y9o2v_1vp"/><g filter="url(#igSm1de)"><rect class="n4w7_lbsm"/></g><g filter="url(#ikIVs8c)"><rect class="ll7-x9noj"/></g><path fill="url(#iFOYC3d)" class="vvfq5ll-q"/><path fill="url(#i1s9tCb)" class="vvfq5ll-q"/><path fill="url(#iWqmWIb)" class="vvfq5ll-q"/><path fill="url(#iDlupvJ)" class="vvfq5ll-q"/><path fill="url(#iFfplsd)" class="vvfq5ll-q"/><path fill="url(#iyKDmNr)" class="vvfq5ll-q"/><g filter="url(#ifxInKe)"><path stroke="url(#i4RCO5d)" class="fdzd0w94z"/></g><path fill="url(#iRoMMGc)" class="qsy52ibya"/><path fill="url(#iEcpAEd)" class="zwjh5j1bq"/><path fill="url(#ii7qwZd)" class="zwjh5j1bq"/><path fill="url(#ij2iXEe)" class="gevugumku"/><path fill="url(#iMqjmrd)" class="gevugumku"/><path fill="url(#ipr1SRd)" class="gevugumku"/><g filter="url(#imVaNWc)"><path stroke="url(#iTKxIod)" class="j1z9_nb6r"/></g><g filter="url(#iqiqEIb)"><path stroke="url(#iKQiuTy)" class="b6j70vs7g"/></g><g filter="url(#iPFIYPe)"><path stroke="url(#iebesIc)" class="phm13ccty"/></g><g filter="url(#isk3Vvz)"><path stroke="url(#igy26Sc)" class="gj5iykbty"/></g><g filter="url(#iiATrQc)"><circle class="qnb_jub0s"/></g><g filter="url(#iRq7Vbc)"><path stroke="url(#itjNoac)" class="nw6tok6ff"/></g><path fill="url(#i0joHVb)" class="h6xn5fbmc"/><path fill="url(#ihm6BUb)" class="uneb7ibsn"/><g filter="url(#idutTFb)"><rect class="e8un5y5xg"/></g><g filter="url(#iSO0x6c)"><rect class="nctyhprxk"/></g><rect fill="url(#ivMiVGc)" class="aigbeze1y"/><rect fill="url(#iidE81d)" class="aigbeze1y"/><rect fill="url(#iaFWgjH)" class="bp3ancjip"/><rect fill="url(#ikzncrb)" class="bp3ancjip"/><g filter="url(#i46AMab)"><path class="p2x792bkr"/></g><g filter="url(#iFi3zEO)"><path class="b47ei68ou"/></g><g filter="url(#ixb8vTc)"><path class="ykh3ccbxv"/></g><g filter="url(#ingtLec)"><path class="iy1sc6bui"/></g><g filter="url(#iJbmxGd)"><path class="appnzkg6x"/></g><defs><linearGradient id="iWSSExd" x1="16" x2="16" y1="25.8" y2="18.8" gradientUnits="userSpaceOnUse"><stop class="vufggk_xw"/><stop offset="1" class="ovo1ps97q"/></linearGradient><linearGradient id="iGKVmke" x1="17.695" x2="17.695" y1="19.363" y2="15.113" gradientUnits="userSpaceOnUse"><stop class="eoe2-tbfx"/><stop offset="1" class="vufggk_xw"/></linearGradient><linearGradient id="ioVpnte" x1="15.945" x2="15.945" y1="17.254" y2="19.16" gradientUnits="userSpaceOnUse"><stop class="thstu_bgr"/><stop offset="1" class="r_bt1_bev"/></linearGradient><linearGradient id="i74v5xW" x1="11.133" x2="13.945" y1="18.41" y2="18.41" gradientUnits="userSpaceOnUse"><stop class="rfj4_nb0t"/><stop offset="1" class="nte9hcb9z"/></linearGradient><linearGradient id="iThWNOe" x1="21.133" x2="22.872" y1="24.363" y2="26.061" gradientUnits="userSpaceOnUse"><stop class="y_hmurbuu"/><stop offset="1" class="tbwfn1b0x"/></linearGradient><linearGradient id="iWcxKJS" x1="22.289" x2="25.506" y1="31.363" y2="26.508" gradientUnits="userSpaceOnUse"><stop class="taw97abnp"/><stop offset="1" class="mkfcaqb4u"/></linearGradient><linearGradient id="iIE1s5d" x1="8.351" x2="5.883" y1="23.644" y2="25.175" gradientUnits="userSpaceOnUse"><stop class="typqntlrg"/><stop offset="1" class="o8jfgsb_m"/></linearGradient><linearGradient id="iy0cNdc" x1="1.946" x2="4.133" y1="26.8" y2="25.988" gradientUnits="userSpaceOnUse"><stop class="typqntlrg"/><stop offset="1" class="uxtq7coxo"/></linearGradient><linearGradient id="iTvDSZK" x1="9.914" x2="7.32" y1="30.769" y2="27.988" gradientUnits="userSpaceOnUse"><stop class="typqntlrg"/><stop offset="1" class="uxtq7coxo"/></linearGradient><linearGradient id="i7AYAQb" x1="1.133" x2="1.133" y1="25.738" y2="32.175" gradientUnits="userSpaceOnUse"><stop class="m8_7yqbwl"/><stop offset=".602" class="mn3u5gbvi"/><stop offset=".854" class="p1mp0z1-p"/></linearGradient><linearGradient id="iEjLGvd" x1="5.525" x2="5.525" y1="30" y2="28.215" gradientUnits="userSpaceOnUse"><stop class="b3sjieb8s"/><stop offset="1" class="xswr_-nki"/></linearGradient><linearGradient id="igzCpKd" x1="7.476" x2="10.82" y1="27.353" y2="27.353" gradientUnits="userSpaceOnUse"><stop class="x2pu-5b3c"/><stop offset="1" class="p1mp0z1-p"/></linearGradient><linearGradient id="iLwt9od" x1="3.804" x2="-.149" y1="27.353" y2="29.097" gradientUnits="userSpaceOnUse"><stop class="x2pu-5b3c"/><stop offset=".487" class="p1mp0z1-p"/></linearGradient><linearGradient id="iJxJfke" x1="15.61" x2="13.235" y1="29.004" y2="29.004" gradientUnits="userSpaceOnUse"><stop class="m8_7yqbwl"/><stop offset=".597" class="mn3u5gbvi"/><stop offset="1" class="p1mp0z1-p"/></linearGradient><linearGradient id="iZsdPTb" x1="14.735" x2="14.735" y1="29.84" y2="28.504" gradientUnits="userSpaceOnUse"><stop class="b3sjieb8s"/><stop offset="1" class="xswr_-nki"/></linearGradient><linearGradient id="iCRqyLb" x1="14.633" x2="14.633" y1="27.858" y2="26.675" gradientUnits="userSpaceOnUse"><stop class="x2pu-5b3c"/><stop offset="1" class="p1mp0z1-p"/></linearGradient><linearGradient id="iXFzXIe" x1="13.61" x2="11.235" y1="29.004" y2="29.004" gradientUnits="userSpaceOnUse"><stop class="m8_7yqbwl"/><stop offset=".597" class="mn3u5gbvi"/><stop offset="1" class="p1mp0z1-p"/></linearGradient><linearGradient id="iod8plc" x1="12.735" x2="12.735" y1="29.84" y2="28.504" gradientUnits="userSpaceOnUse"><stop class="b3sjieb8s"/><stop offset="1" class="xswr_-nki"/></linearGradient><linearGradient id="iUxF1wp" x1="12.633" x2="12.633" y1="27.858" y2="26.675" gradientUnits="userSpaceOnUse"><stop class="x2pu-5b3c"/><stop offset="1" class="p1mp0z1-p"/></linearGradient><linearGradient id="iNjvS7c" x1="11.82" x2="9.445" y1="29.004" y2="29.004" gradientUnits="userSpaceOnUse"><stop class="m8_7yqbwl"/><stop offset=".597" class="mn3u5gbvi"/><stop offset="1" class="p1mp0z1-p"/></linearGradient><linearGradient id="iDZrZos" x1="10.945" x2="10.945" y1="29.84" y2="28.504" gradientUnits="userSpaceOnUse"><stop class="b3sjieb8s"/><stop offset="1" class="xswr_-nki"/></linearGradient><linearGradient id="iVOitqb" x1="10.842" x2="10.842" y1="27.858" y2="26.675" gradientUnits="userSpaceOnUse"><stop class="x2pu-5b3c"/><stop offset="1" class="p1mp0z1-p"/></linearGradient><linearGradient id="i0BH2EC" x1="14.695" x2="14.695" y1="27.8" y2="12.05" gradientUnits="userSpaceOnUse"><stop class="alcuao69o"/><stop offset=".697" class="vc9ashkmk"/></linearGradient><linearGradient id="iZuiNkb" x1="9.399" x2="9.399" y1="27.863" y2="24.05" gradientUnits="userSpaceOnUse"><stop class="fyfh3xy-q"/><stop offset="1" class="fc0vs1j3c"/></linearGradient><linearGradient id="itL7Gkc" x1="7.633" x2="10.445" y1="25.05" y2="23.175" gradientUnits="userSpaceOnUse"><stop class="fyfh3xy-q"/><stop offset="1" class="fc0vs1j3c"/></linearGradient><linearGradient id="i9MqFSb" x1="21.973" x2="21.973" y1="25.738" y2="32.175" gradientUnits="userSpaceOnUse"><stop class="m8_7yqbwl"/><stop offset=".602" class="mn3u5gbvi"/><stop offset=".854" class="p1mp0z1-p"/></linearGradient><linearGradient id="ikGPtLe" x1="26.365" x2="26.365" y1="30" y2="28.215" gradientUnits="userSpaceOnUse"><stop class="b3sjieb8s"/><stop offset="1" class="xswr_-nki"/></linearGradient><linearGradient id="i01svId" x1="16.07" x2="19.82" y1="29.004" y2="29.004" gradientUnits="userSpaceOnUse"><stop class="m8_7yqbwl"/><stop offset=".597" class="mn3u5gbvi"/><stop offset="1" class="p1mp0z1-p"/></linearGradient><linearGradient id="iloLJVd" x1="17.16" x2="17.16" y1="29.84" y2="28.504" gradientUnits="userSpaceOnUse"><stop class="b3sjieb8s"/><stop offset="1" class="xswr_-nki"/></linearGradient><linearGradient id="i1aVYGe" x1="17.057" x2="17.057" y1="27.858" y2="26.675" gradientUnits="userSpaceOnUse"><stop class="x2pu-5b3c"/><stop offset="1" class="p1mp0z1-p"/></linearGradient><linearGradient id="ix6EKdb" x1="16.523" x2="14.992" y1="27.858" y2="27.858" gradientUnits="userSpaceOnUse"><stop class="x2pu-5b3c"/><stop offset=".684" class="p1mp0z1-p"/></linearGradient><linearGradient id="iDaD0pc" x1="18.07" x2="21.289" y1="29.004" y2="29.004" gradientUnits="userSpaceOnUse"><stop class="m8_7yqbwl"/><stop offset=".597" class="mn3u5gbvi"/><stop offset="1" class="p1mp0z1-p"/></linearGradient><linearGradient id="iHoBVXq" x1="19.16" x2="19.16" y1="29.84" y2="28.504" gradientUnits="userSpaceOnUse"><stop class="b3sjieb8s"/><stop offset="1" class="xswr_-nki"/></linearGradient><linearGradient id="iirNGse" x1="19.057" x2="19.057" y1="27.858" y2="26.675" gradientUnits="userSpaceOnUse"><stop class="x2pu-5b3c"/><stop offset="1" class="p1mp0z1-p"/></linearGradient><linearGradient id="iIlhVsi" x1="20.07" x2="23.289" y1="29.004" y2="29.004" gradientUnits="userSpaceOnUse"><stop class="m8_7yqbwl"/><stop offset=".597" class="mn3u5gbvi"/><stop offset="1" class="p1mp0z1-p"/></linearGradient><linearGradient id="ihroxTd" x1="21.16" x2="21.16" y1="29.84" y2="28.504" gradientUnits="userSpaceOnUse"><stop class="b3sjieb8s"/><stop offset="1" class="xswr_-nki"/></linearGradient><linearGradient id="iOmHQDN" x1="21.057" x2="21.057" y1="27.858" y2="26.675" gradientUnits="userSpaceOnUse"><stop class="x2pu-5b3c"/><stop offset="1" class="p1mp0z1-p"/></linearGradient><linearGradient id="idZAV4d" x1="27.793" x2="27.793" y1="27.8" y2="11.925" gradientUnits="userSpaceOnUse"><stop class="alcuao69o"/><stop offset="1" class="felxy0bxi"/></linearGradient><linearGradient id="itfPv9b" x1="22.499" x2="22.499" y1="27.863" y2="20.863" gradientUnits="userSpaceOnUse"><stop class="fyfh3xy-q"/><stop offset="1" class="fc0vs1j3c"/></linearGradient><linearGradient id="iieJSsc" x1="25.133" x2="23.883" y1="23.488" y2="22.55" gradientUnits="userSpaceOnUse"><stop class="shfkvcb_p"/><stop offset="1" class="jgh14cpca"/></linearGradient><linearGradient id="iSDE2Ec" x1="21.57" x2="25.718" y1="5.676" y2="24.776" gradientUnits="userSpaceOnUse"><stop class="hn7se7s5g"/><stop offset="1" class="a457lmbso"/></linearGradient><linearGradient id="iWqjTXd" x1="14.851" x2="14.851" y1="12.769" y2="17.582" gradientUnits="userSpaceOnUse"><stop class="c_lhr7b2d"/><stop offset="1" class="nv7ixbu1g"/></linearGradient><linearGradient id="iAodz4b" x1="15.429" x2="15.429" y1="16.91" y2="14.879" gradientUnits="userSpaceOnUse"><stop class="agira0bfw"/><stop offset="1" class="zi5mjybwh"/></linearGradient><linearGradient id="ivw7vee" x1="14.883" x2="14.117" y1="16.175" y2="16.175" gradientUnits="userSpaceOnUse"><stop class="agira0bfw"/><stop offset="1" class="zi5mjybwh"/></linearGradient><linearGradient id="iMdJw2D" x1="17.164" x2="18.695" y1="16.175" y2="16.175" gradientUnits="userSpaceOnUse"><stop class="agira0bfw"/><stop offset="1" class="zi5mjybwh"/></linearGradient><linearGradient id="ibVzuIb" x1="14.867" x2="16.398" y1="16.175" y2="16.175" gradientUnits="userSpaceOnUse"><stop class="agira0bfw"/><stop offset="1" class="zi5mjybwh"/></linearGradient><linearGradient id="iFOYC3d" x1="15.945" x2="15.945" y1="-.325" y2="10.925" gradientUnits="userSpaceOnUse"><stop class="g4mzwkbih"/><stop offset="1" class="cjcqe0bjj"/></linearGradient><linearGradient id="i1s9tCb" x1="15.945" x2="16.258" y1="12.988" y2="8.8" gradientUnits="userSpaceOnUse"><stop class="nq46cvbaa"/><stop offset="1" class="ey7lxtiwe"/></linearGradient><linearGradient id="i4RCO5d" x1="22.062" x2="12.976" y1="7.013" y2="7.013" gradientUnits="userSpaceOnUse"><stop class="bgvilhbnj"/><stop offset="1" class="sy9afdcki"/></linearGradient><linearGradient id="iTKxIod" x1="11.976" x2="14.156" y1="27.3" y2="14.806" gradientUnits="userSpaceOnUse"><stop class="iyg7mtbzf"/><stop offset="1" class="i2oid9pls"/></linearGradient><linearGradient id="iKQiuTy" x1="8.101" x2="2.32" y1="27.644" y2="27.644" gradientUnits="userSpaceOnUse"><stop class="q7ykrcl2k"/><stop offset="1" class="u8sx3-bax"/></linearGradient><linearGradient id="iebesIc" x1="28.63" x2="24.474" y1="27.754" y2="27.754" gradientUnits="userSpaceOnUse"><stop class="q7ykrcl2k"/><stop offset="1" class="u8sx3-bax"/></linearGradient><linearGradient id="igy26Sc" x1="27.82" x2="27.82" y1="26.222" y2="29.066" gradientUnits="userSpaceOnUse"><stop class="q7ykrcl2k"/><stop offset="1" class="u8sx3-bax"/></linearGradient><linearGradient id="itjNoac" x1="25.82" x2="24.245" y1="19.175" y2="15.394" gradientUnits="userSpaceOnUse"><stop class="hn7se7s5g"/><stop offset="1" class="a457lmbso"/></linearGradient><linearGradient id="ivMiVGc" x1="18.276" x2="16.794" y1="8.355" y2="8.355" gradientUnits="userSpaceOnUse"><stop offset=".006" class="p6vd50w9p"/><stop offset="1" class="fwtna0oas"/></linearGradient><linearGradient id="iidE81d" x1="16.794" x2="16.794" y1="9.426" y2="8.863" gradientUnits="userSpaceOnUse"><stop offset=".006" class="vylhu7i4w"/><stop offset="1" class="ueu24dben"/></linearGradient><linearGradient id="iaFWgjH" x1="15.276" x2="13.793" y1="8.355" y2="8.355" gradientUnits="userSpaceOnUse"><stop offset=".006" class="p6vd50w9p"/><stop offset="1" class="fwtna0oas"/></linearGradient><linearGradient id="ikzncrb" x1="13.793" x2="13.793" y1="9.426" y2="8.863" gradientUnits="userSpaceOnUse"><stop offset=".006" class="vylhu7i4w"/><stop offset="1" class="ueu24dben"/></linearGradient><filter id="iJdYbXd" width="8.02" height="6.113" x="11.596" y="11.323" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1568" stdDeviation=".25"/></filter><filter id="iSD0Htc" width="1.516" height="2.676" x="18.1" y="15.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1568" stdDeviation=".25"/></filter><filter id="iqWy8yc" width="3.742" height="3.742" x="26.465" y="19.496" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1568" stdDeviation=".5"/></filter><filter id="iewrkMe" width="13.612" height="21.5" x="2.343" y="5.863" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.879167 0 0 0 0 0.287519 0 0 0 0 0.0256423 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_1568"/></filter><filter id="iA4P4uc" width="7.631" height="10.319" x="21.082" y="6.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1568" stdDeviation=".5"/></filter><filter id="igSm1de" width="1.641" height="3.871" x="17.78" y="12.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1568" stdDeviation=".25"/></filter><filter id="ikIVs8c" width="1.641" height="3.871" x="15.804" y="12.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1568" stdDeviation=".25"/></filter><filter id="ifxInKe" width="10.711" height="7.406" x="13.101" y="2.613" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1568" stdDeviation=".75"/></filter><filter id="imVaNWc" width="6.327" height="10.52" x="9.731" y="16.581" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1568" stdDeviation=".5"/></filter><filter id="iqiqEIb" width="6.327" height="2.795" x="2.643" y="25.349" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1568" stdDeviation=".25"/></filter><filter id="iPFIYPe" width="6.749" height="2.795" x="22.803" y="25.459" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1568" stdDeviation=".25"/></filter><filter id="isk3Vvz" width="1.3" height="2.344" x="27.686" y="26.629" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1568" stdDeviation=".25"/></filter><filter id="iiATrQc" width="1.516" height="1.516" x="28.453" y="25.406" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1568" stdDeviation=".25"/></filter><filter id="iRq7Vbc" width="3.944" height="5.975" x="23.989" y="13.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1568" stdDeviation=".5"/></filter><filter id="idutTFb" width="1.792" height="2.8" x="16.352" y="7.119" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1568" stdDeviation=".2"/></filter><filter id="iSO0x6c" width="1.792" height="2.8" x="13.329" y="7.119" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1568" stdDeviation=".2"/></filter><filter id="i46AMab" width=".8" height="1.871" x="17.256" y="7.26" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1568" stdDeviation=".15"/></filter><filter id="iFi3zEO" width=".8" height="1.871" x="14.217" y="7.26" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1568" stdDeviation=".15"/></filter><filter id="ixb8vTc" width="3.172" height="3.281" x="17.935" y="5.238" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1568" stdDeviation=".375"/></filter><filter id="ingtLec" width="1.859" height="1.828" x="15.851" y="2.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1568" stdDeviation=".25"/></filter><filter id="iJbmxGd" width="1.859" height="1.828" x="14.596" y="2.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1568" stdDeviation=".25"/></filter><radialGradient id="iDI97zb" cx="0" cy="0" r="1" gradientTransform="matrix(5 -6.25 6.25 5 24.133 28.55)" gradientUnits="userSpaceOnUse"><stop class="df5ylr0_j"/><stop offset="1" class="pymbuut6f"/></radialGradient><radialGradient id="iv07vyb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.28124 -2.875 9.99282 -7.92902 29.008 26.675)" gradientUnits="userSpaceOnUse"><stop class="fb2xhh9wn"/><stop offset="1" class="lnp65bbdj"/></radialGradient><radialGradient id="iVR7l7d" cx="0" cy="0" r="1" gradientTransform="matrix(3.66451 1.625 -8.0907 18.24517 2.843 11.738)" gradientUnits="userSpaceOnUse"><stop class="fb2xhh9wn"/><stop offset="1" class="lnp65bbdj"/></radialGradient><radialGradient id="iNYxKuc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.171 1.875 -3.7059 -4.2909 11.57 11.05)" gradientUnits="userSpaceOnUse"><stop offset=".326" class="oldq9ubhv"/><stop offset="1" class="sghtj2bsd"/></radialGradient><radialGradient id="itIOphT" cx="0" cy="0" r="1" gradientTransform="matrix(8.99995 4.93754 -6.60152 12.03299 24.351 25.52)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="x2pu-5b3c"/><stop offset="1" class="p1mp0z1-p"/></radialGradient><radialGradient id="ic4UUBe" cx="0" cy="0" r="1" gradientTransform="matrix(-8.4375 .54134 -.30118 -4.69432 30.883 27.353)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="x2pu-5b3c"/><stop offset="1" class="p1mp0z1-p"/></radialGradient><radialGradient id="iunIOtb" cx="0" cy="0" r="1" gradientTransform="rotate(123.864 3.42 11.398)scale(1.43009 1.99926)" gradientUnits="userSpaceOnUse"><stop class="agira0bfw"/><stop offset="1" class="zi5mjybwh"/></radialGradient><radialGradient id="iWqmWIb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5625 1.5 -1.98581 -2.06854 13.07 9.925)" gradientUnits="userSpaceOnUse"><stop class="o3_2jtm_k"/><stop offset="1" class="ey7lxtiwe"/></radialGradient><radialGradient id="iDlupvJ" cx="0" cy="0" r="1" gradientTransform="matrix(2.8125 1.6875 -4.09877 6.83127 9.633 4.925)" gradientUnits="userSpaceOnUse"><stop class="fb2xhh9wn"/><stop offset="1" class="lnp65bbdj"/></radialGradient><radialGradient id="iFfplsd" cx="0" cy="0" r="1" gradientTransform="rotate(39.867 3.583 20.918)scale(1.85253 1.53368)" gradientUnits="userSpaceOnUse"><stop class="kptg8ab8i"/><stop offset=".573" class="ek53y2bjn"/></radialGradient><radialGradient id="iyKDmNr" cx="0" cy="0" r="1" gradientTransform="matrix(.375 1.51563 -1.25475 .31046 16.367 2.144)" gradientUnits="userSpaceOnUse"><stop class="kptg8ab8i"/><stop offset=".751" class="ek53y2bjn"/></radialGradient><radialGradient id="iRoMMGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.6775 -8.875 0 16.383 6.676)" gradientUnits="userSpaceOnUse"><stop class="dld8zrszl"/><stop offset=".706" class="ujidk80nm"/><stop offset="1" class="c4fam1b4x"/></radialGradient><radialGradient id="iEcpAEd" cx="0" cy="0" r="1" gradientTransform="rotate(84.514 5.98 13.065)scale(5.5567 11.0243)" gradientUnits="userSpaceOnUse"><stop offset=".012" class="dld8zrszl"/><stop offset=".706" class="ujidk80nm"/><stop offset="1" class="c4fam1b4x"/></radialGradient><radialGradient id="ii7qwZd" cx="0" cy="0" r="1" gradientTransform="rotate(152.152 9.66 5.872)scale(3.74635 3.53909)" gradientUnits="userSpaceOnUse"><stop class="tarh7bshh"/><stop offset="1" class="wc7j5zb-h"/></radialGradient><radialGradient id="ij2iXEe" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.06296 -6.19471 0 16.25 9.29)" gradientUnits="userSpaceOnUse"><stop class="kjeu_kbpf"/><stop offset=".455" class="ujidk80nm"/><stop offset="1" class="c4fam1b4x"/></radialGradient><radialGradient id="iMqjmrd" cx="0" cy="0" r="1" gradientTransform="rotate(-26.65 33.215 -26.95)scale(4.73767)" gradientUnits="userSpaceOnUse"><stop offset=".726" class="wc7j5zb-h"/><stop offset=".897" class="tarh7bshh"/></radialGradient><radialGradient id="ipr1SRd" cx="0" cy="0" r="1" gradientTransform="rotate(137.62 7.635 8.83)scale(3.38439)" gradientUnits="userSpaceOnUse"><stop class="tarh7bshh"/><stop offset="1" class="wc7j5zb-h"/></radialGradient><radialGradient id="i0joHVb" cx="0" cy="0" r="1" gradientTransform="matrix(.43304 -.49348 .49733 .43642 14.779 11.629)" gradientUnits="userSpaceOnUse"><stop class="zaeth0b6d"/><stop offset="1" class="un38w7b3t"/></radialGradient><radialGradient id="ihm6BUb" cx="0" cy="0" r="1" gradientTransform="matrix(.43304 -.49348 .49733 .43642 16.716 11.629)" gradientUnits="userSpaceOnUse"><stop class="zaeth0b6d"/><stop offset="1" class="un38w7b3t"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:orangutan" /></template>
<style>
.a457lmbso {
  stop-color: var(--svg-color--fac371, #FAC371);
  stop-opacity: 0;
}

.agira0bfw {
  stop-color: var(--svg-color--d4431d, #D4431D);
}

.aigbeze1y {
  width: 0.992px;
  height: 2px;
  x: 16.949px;
  y: 7.355px;
  rx: 0.496px;
}

.alcuao69o {
  stop-color: var(--svg-color--fc601d, #FC601D);
}

.appnzkg6x {
  fill: var(--svg-color--ffb661, #FFB661);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M15.096 2.566v.828h.859z");
}

.b3sjieb8s {
  stop-color: var(--svg-color--49325f, #49325F);
}

.b47ei68ou {
  stroke: var(--svg-color--725f62, #725F62);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.617 7.66v1.07");
}

.b6j70vs7g {
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M3.143 26H7.07c.69 0 1.25.559 1.25 1.25v.394");
}

.bgvilhbnj {
  stop-color: var(--svg-color--ffc85f, #FFC85F);
}

.biivzhtww {
  cx: 28.336px;
  cy: 21.367px;
  r: 0.871px;
  fill: var(--svg-color--ff8e53, #FF8E53);
}

.bp3ancjip {
  width: 0.992px;
  height: 2px;
  x: 13.949px;
  y: 7.355px;
  rx: 0.496px;
}

.bwgmbd-bx {
  fill: var(--svg-color--7c757c, #7C757C);
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  d: path("M18.6 16h.516v1.675H18.6z");
}

.c_lhr7b2d {
  stop-color: var(--svg-color--ff7a48, #FF7A48);
}

.c4fam1b4x {
  stop-color: var(--svg-color--4b3449, #4B3449);
}

.cjcqe0bjj {
  stop-color: var(--svg-color--f3602d, #F3602D);
}

.df5ylr0_j {
  stop-color: var(--svg-color--c53e16, #C53E16);
}

.dld8zrszl {
  stop-color: var(--svg-color--7f7e80, #7F7E80);
}

.ds_nv9bxv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M22.383 7.738h.347a2 2 0 0 1 1.833 1.199l2.85 6.52");
}

.e8un5y5xg {
  width: 0.992px;
  height: 2px;
  x: 16.752px;
  y: 7.519px;
  fill: var(--svg-color--453f48, #453F48);
  rx: 0.496px;
}

.ek53y2bjn {
  stop-color: var(--svg-color--d6620d, #D6620D);
  stop-opacity: 0;
}

.eoe2-tbfx {
  stop-color: var(--svg-color--29191f, #29191F);
  stop-opacity: 0;
}

.erm4t9r7t {
  d: path("M10.375 29.363h-5.65l-2.59-6.48a2.56 2.56 0 0 1 2.38-3.52h4.21l3.13 7.82c.42 1.05-.35 2.18-1.48 2.18");
}

.ey7lxtiwe {
  stop-color: var(--svg-color--c3442c, #C3442C);
  stop-opacity: 0;
}

.fb2xhh9wn {
  stop-color: var(--svg-color--ff8d3c, #FF8D3C);
}

.fc0vs1j3c {
  stop-color: var(--svg-color--ea5a36, #EA5A36);
  stop-opacity: 0;
}

.fdzd0w94z {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M14.601 4.363h4.211a3.25 3.25 0 0 1 3.25 3.25v.906");
}

.felxy0bxi {
  stop-color: var(--svg-color--ff8a38, #FF8A38);
}

.fmvra1brm {
  d: path("M12.755 29.363h-.83c-.22 0-.4-.18-.4-.4v-2.61h2.42v1.82c0 .66-.53 1.19-1.19 1.19");
}

.fr9nhqbin {
  d: path("M21.145 29.363h.83c.22 0 .4-.18.4-.4v-2.61h-2.43v1.82c0 .66.54 1.19 1.2 1.19");
}

.ft5dv1b6b {
  fill: none;
}

.fwtna0oas {
  stop-color: var(--svg-color--2e2127, #2E2127);
}

.fyfh3xy-q {
  stop-color: var(--svg-color--ed471e, #ED471E);
}

.g173qtpqz {
  d: path("M14.883 12.237v3.77c-.055-.033-.147-.023-.176.032a1.18 1.18 0 0 1-1.041.624a1.19 1.19 0 0 1-1.185-1.197V11.55c0-.4.194-.317.492-.188c.195.084.434.188.693.188c.547 0 1.008.375 1.144.884q.029-.102.072-.198");
}

.g4mzwkbih {
  stop-color: var(--svg-color--ffa153, #FFA153);
}

.gevugumku {
  d: path("M15.945 15.353c-1.93 0-3.49-1.56-3.49-3.49a3.487 3.487 0 0 1 3.49-3.49c1.93 0 3.49 1.56 3.49 3.49s-1.56 3.49-3.49 3.49");
}

.gfypu3b_p {
  d: path("M21.475 11.823h-10.95v14.67h10.95z");
}

.gj5iykbty {
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M28.336 27.129v1.343");
}

.gr2e7bywt {
  fill: var(--svg-color--636363, #636363);
  d: path("M21.475 11.823h-10.95v14.67h10.95z");
}

.h060x4brd {
  fill-rule: evenodd;
  d: path("M3.765 25.343h-.82c-.555.005-1 .453-1 1.01s.445 1.005 1 1.01v.92c0 .6.48 1.08 1.08 1.08h3.07a2.01 2.01 0 0 0 0-4.02z");
}

.h6xn5fbmc {
  d: path("M14.93 11.793a.43.43 0 1 0 0-.86a.43.43 0 0 0 0 .86");
}

.hn7se7s5g {
  stop-color: var(--svg-color--fac371, #FAC371);
}

.i2oid9pls {
  stop-color: var(--svg-color--fca95d, #FCA95D);
  stop-opacity: 0;
}

.i8cm5uskj {
  fill-rule: evenodd;
  d: path("M28.125 25.343h-3.33a2.01 2.01 0 0 0 0 4.02h3.07c.6 0 1.08-.48 1.08-1.08v-.92c.555-.005 1-.453 1-1.01s-.445-1.005-1-1.01z");
}

.isgrikb0u {
  d: path("M15.945 25.413c0-.69.2-1.35.58-1.92l3.06-4.59c.23-.34.31-.77.22-1.17l-2.56-11.37h4.89c1.7 0 3.22 1.05 3.82 2.63l3.05 7.49c.17.42-.14.87-.59.87c-.36 0-.7-.1-1-.28c-.1-.06-.21.05-.15.15c.41.69.38 1.56-.08 2.21l-3.85 5.5c-.4.57-.78 1.17-1.08 1.8c-.16.38-.53.63-.96.63c-.41 0-.77-.23-.95-.57c-.05-.1-.19-.1-.24 0a1.075 1.075 0 0 1-1.9 0c-.05-.1-.19-.1-.24 0a1.074 1.074 0 0 1-2.02-.44z");
}

.iy1sc6bui {
  fill: var(--svg-color--ffb661, #FFB661);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M17.21 2.566v.828h-.859z");
}

.iyg7mtbzf {
  stop-color: var(--svg-color--fba95d, #FBA95D);
}

.j1z9_nb6r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M11.133 17.676v0a1.98 1.98 0 0 0 .247 1.751l3.025 4.393a2 2 0 0 1 .353 1.134v.846");
}

.jgh14cpca {
  stop-color: var(--svg-color--e24b0c, #E24B0C);
  stop-opacity: 0;
}

.kjeu_kbpf {
  stop-color: var(--svg-color--6d6c6f, #6D6C6F);
}

.kptg8ab8i {
  stop-color: var(--svg-color--e36d17, #E36D17);
}

.ll7-x9noj {
  width: 0.641px;
  height: 2.871px;
  x: 16.304px;
  y: 12.992px;
  fill: var(--svg-color--fc784b, #FC784B);
  rx: 0.32px;
}

.lnp65bbdj {
  stop-color: var(--svg-color--f48434, #F48434);
  stop-opacity: 0;
}

.m0q9s4bvb {
  d: path("M13.666 11.55c-.655 0-1.185-.66-1.185 0v3.915a1.182 1.182 0 0 0 2.226.574c.036-.068.17-.068.207 0a1.182 1.182 0 0 0 2.082 0c.037-.068.17-.068.207 0c.201.372.592.624 1.041.624a1.19 1.19 0 0 0 1.185-1.197V11.55c0-.662-.53 0-1.185 0a1.19 1.19 0 0 0-1.145.884a1.19 1.19 0 0 0-1.144-.885a1.19 1.19 0 0 0-1.145.885a1.19 1.19 0 0 0-1.144-.885");
}

.m8_7yqbwl {
  stop-color: var(--svg-color--645f67, #645F67);
}

.mkfcaqb4u {
  stop-color: var(--svg-color--9a3f0c, #9A3F0C);
  stop-opacity: 0;
}

.mn3u5gbvi {
  stop-color: var(--svg-color--332f37, #332F37);
}

.mrdsf44xp {
  d: path("M15.955 25.413c0-.69-.2-1.35-.58-1.92l-3.06-4.59c-.23-.34-.31-.77-.22-1.17l2.56-11.37h-4.89c-1.7 0-3.22 1.05-3.82 2.63l-3.05 7.49c-.18.42.13.88.58.88c.36 0 .7-.1 1-.28c.1-.06.21.05.15.15c-.41.69-.38 1.56.08 2.21l3.85 5.5c.4.57.78 1.17 1.08 1.8c.17.37.54.62.96.62c.41 0 .77-.23.95-.57c.05-.1.19-.1.24 0a1.075 1.075 0 0 0 1.9 0c.05-.1.19-.1.24 0a1.075 1.075 0 0 0 2.02-.44h.01z");
}

.n4w7_lbsm {
  width: 0.641px;
  height: 2.871px;
  x: 18.28px;
  y: 12.992px;
  fill: var(--svg-color--fc784b, #FC784B);
  rx: 0.32px;
}

.nctyhprxk {
  width: 0.992px;
  height: 2px;
  x: 13.729px;
  y: 7.519px;
  fill: var(--svg-color--453f48, #453F48);
  rx: 0.496px;
}

.nenme4bly {
  d: path("M19.145 29.363h.83c.22 0 .4-.18.4-.4v-2.61h-2.43v1.82c0 .66.54 1.19 1.2 1.19");
}

.nq46cvbaa {
  stop-color: var(--svg-color--c3442c, #C3442C);
}

.nte9hcb9z {
  stop-color: var(--svg-color--7c757c, #7C757C);
  stop-opacity: 0;
}

.nv7ixbu1g {
  stop-color: var(--svg-color--ec3f21, #EC3F21);
}

.nw6tok6ff {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("m25.289 14.926l1.343 3.374");
}

.o3_2jtm_k {
  stop-color: var(--svg-color--a6311b, #A6311B);
}

.o8jfgsb_m {
  stop-color: var(--svg-color--f16d29, #F16D29);
}

.ogrs9bbhe {
  d: path("M14.755 29.363h-.83c-.22 0-.4-.18-.4-.4v-2.61h2.42v1.82c0 .66-.53 1.19-1.19 1.19");
}

.oldq9ubhv {
  stop-color: var(--svg-color--c84b15, #C84B15);
}

.ovo1ps97q {
  stop-color: var(--svg-color--4e4852, #4E4852);
}

.p1mp0z1-p {
  stop-color: var(--svg-color--29262c, #29262C);
}

.p2x792bkr {
  stroke: var(--svg-color--725f62, #725F62);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.656 7.66v1.07");
}

.p6vd50w9p {
  stop-color: var(--svg-color--5f5254, #5F5254);
}

.phm13ccty {
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M29.052 26.109h-4.349c-.69 0-1.25.56-1.25 1.25v.395");
}

.pymbuut6f {
  stop-color: var(--svg-color--ff8138, #FF8138);
}

.q7ykrcl2k {
  stop-color: var(--svg-color--78727c, #78727C);
}

.qnb_jub0s {
  cx: 29.211px;
  cy: 26.164px;
  r: 0.258px;
  fill: var(--svg-color--78727c, #78727C);
}

.qsy52ibya {
  d: path("M12.664 10.67a.29.29 0 0 0-.161-.364a2.57 2.57 0 0 1-1.558-2.363a2.557 2.557 0 0 1 2.56-2.58h4.86c1.43 0 2.58 1.15 2.58 2.57a2.58 2.58 0 0 1-1.559 2.372a.29.29 0 0 0-.16.364c.135.372.209.774.209 1.194c0 1.93-1.56 3.49-3.49 3.49a3.487 3.487 0 0 1-3.281-4.683");
}

.r_bt1_bev {
  stop-color: var(--svg-color--371d2b, #371D2B);
}

.rfj4_nb0t {
  stop-color: var(--svg-color--7c757c, #7C757C);
}

.sc6kk-2pn {
  d: path("M10.965 29.363h-.83c-.22 0-.4-.18-.4-.4v-2.61h2.42v1.82c0 .66-.53 1.19-1.19 1.19");
}

.sghtj2bsd {
  stop-color: var(--svg-color--c54c16, #C54C16);
  stop-opacity: 0;
}

.shfkvcb_p {
  stop-color: var(--svg-color--e24b0c, #E24B0C);
}

.sy9afdcki {
  stop-color: var(--svg-color--ffc85f, #FFC85F);
  stop-opacity: 0;
}

.tarh7bshh {
  stop-color: var(--svg-color--7d7c7f, #7D7C7F);
}

.taw97abnp {
  stop-color: var(--svg-color--9a3f0c, #9A3F0C);
}

.tbwfn1b0x {
  stop-color: var(--svg-color--e25c11, #E25C11);
  stop-opacity: 0;
}

.thstu_bgr {
  stop-color: var(--svg-color--5c535e, #5C535E);
}

.typqntlrg {
  stop-color: var(--svg-color--d03913, #D03913);
}

.u8sx3-bax {
  stop-color: var(--svg-color--78727c, #78727C);
  stop-opacity: 0;
}

.ueu24dben {
  stop-color: var(--svg-color--34222c, #34222C);
  stop-opacity: 0;
}

.ujidk80nm {
  stop-color: var(--svg-color--5d5c5f, #5D5C5F);
}

.un38w7b3t {
  stop-color: var(--svg-color--2f2228, #2F2228);
}

.uneb7ibsn {
  d: path("M16.867 11.793a.43.43 0 1 0 0-.86a.43.43 0 0 0 0 .86");
}

.uxtq7coxo {
  stop-color: var(--svg-color--d03913, #D03913);
  stop-opacity: 0;
}

.vc9ashkmk {
  stop-color: var(--svg-color--fd6f28, #FD6F28);
}

.vufggk_xw {
  stop-color: var(--svg-color--29191f, #29191F);
}

.vvfq5ll-q {
  d: path("M17.484 3.163c0 .11.09.2.2.2h1.071c2.31 0 4.19 1.88 4.19 4.19s-1.88 4.19-4.19 4.19h-5.62c-2.31 0-4.19-1.88-4.19-4.19s1.88-4.19 4.19-4.19h1.07a.2.2 0 0 0 .2-.2v-.28a.6.6 0 0 1 .953-.486l.47.34a.2.2 0 0 0 .234 0l.47-.34a.6.6 0 0 1 .952.486z");
}

.vylhu7i4w {
  stop-color: var(--svg-color--34222c, #34222C);
}

.wc7j5zb-h {
  stop-color: var(--svg-color--7d7c7f, #7D7C7F);
  stop-opacity: 0;
}

.wer2ym_va {
  fill-opacity: var(--svg-fill-opacity--0-25, 0.25);
  d: path("M12.336 15.566h7.218v2.044a.8.8 0 0 1-.8.8h-5.618a.8.8 0 0 1-.8-.8z");
}

.wnm6yvi7y {
  fill: var(--svg-color--382e37, #382E37);
  d: path("M13.294 11.823c-.662 0-1.198.536-1.198 1.197v2.718a1.197 1.197 0 0 0 2.354.313a1.198 1.198 0 0 0 2.312 0a1.198 1.198 0 0 0 2.354-.313v-2.717a1.197 1.197 0 0 0-2.354-.313a1.198 1.198 0 0 0-2.312 0a1.2 1.2 0 0 0-1.156-.885");
}

.wzx_ohz0x {
  d: path("M17.164 16.002v-3.748c.186-.415.6-.703 1.08-.703c.259 0 .498-.104.693-.188c.298-.129.492-.212.492.188v3.915a1.182 1.182 0 0 1-2.226.573a.1.1 0 0 0-.04-.037");
}

.x2pu-5b3c {
  stop-color: var(--svg-color--29262c, #29262C);
  stop-opacity: 0;
}

.x4-n5dbmw {
  d: path("M21.775 29.363h5.39l2.59-6.48c.67-1.68-.57-3.52-2.38-3.52h-4.21l-3.03 7.58c-.46 1.16.39 2.42 1.64 2.42");
}

.xk6_c3zqa {
  d: path("M12.336 15.566h7.218v2.044a.8.8 0 0 1-.8.8h-5.618a.8.8 0 0 1-.8-.8z");
}

.xswr_-nki {
  stop-color: var(--svg-color--49325f, #49325F);
  stop-opacity: 0;
}

.y_h1t_b9h {
  d: path("M17.145 29.363h.83c.22 0 .4-.18.4-.4v-2.61h-2.43v1.82c0 .66.54 1.19 1.2 1.19");
}

.y_hmurbuu {
  stop-color: var(--svg-color--e25c11, #E25C11);
}

.y9o2v_1vp {
  d: path("M14.867 16.002v-3.748c.186-.415.6-.703 1.08-.703c.26 0 .499-.104.694-.188c.298-.129.492-.212.492.188v3.915c0 .66-.53 1.197-1.185 1.197c-.45 0-.84-.252-1.042-.624a.1.1 0 0 0-.039-.037");
}

.ykh3ccbxv {
  stroke: var(--svg-color--8a898c, #8A898C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M18.935 6.238c.313.094.985.481 1.172 1.281");
}

.zaeth0b6d {
  stop-color: var(--svg-color--636363, #636363);
}

.zi5mjybwh {
  stop-color: var(--svg-color--d4431d, #D4431D);
  stop-opacity: 0;
}

.zwjh5j1bq {
  d: path("M18.375 10.513h-4.86a2.57 2.57 0 0 1-2.57-2.57a2.557 2.557 0 0 1 2.56-2.58h4.86c1.43 0 2.58 1.15 2.58 2.57s-1.15 2.58-2.57 2.58");
}

</style>
