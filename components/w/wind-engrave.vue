<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/ymh36zb9w.css';
import '../../css/a/aeo__2bgr.css';
import '../../css/j/ji2uddb1b.css';
import '../../css/g/gkf7pdbgi.css';
import '../../css/v/v335rzk7y.css';
import '../../css/a/aaskxzbtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k ymh36zb9w"/><path class="aeo__2bgr wm-a"/><path class="ji2uddb1b wm-shadow"/><path class="gkf7pdbgi wm-a"/><path class="v335rzk7y wm-k"/><path class="aaskxzbtv wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wind-engrave" /></template>
