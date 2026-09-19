<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvaaipbio.css';
import '../../css/v/vy6884uyz.css';
import '../../css/j/jjrkjtb3x.css';
import '../../css/h/hj6wm5bry.css';
import '../../css/q/quzn65tbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvaaipbio"/><rect class="vy6884uyz"/><rect class="jjrkjtb3x"/><rect class="hj6wm5bry"/><path class="quzn65tbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:qr-scan-filled" /></template>
