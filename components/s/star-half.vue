<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skkogyb-m.css';
import '../../css/a/a27c1cbey.css';
import '../../css/q/qgc-emm8e.css';
import '../../css/h/hhe7s3b1e.css';
import '../../css/v/vawm-5bog.css';
import '../../css/e/esy3f6kir.css';
import '../../css/h/hy1ry4bey.css';
import '../../css/r/rp_powb7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skkogyb-m wm-shadow"/><path class="a27c1cbey wm-k"/><path class="qgc-emm8e wm-k"/><path class="hhe7s3b1e wm-k"/><path class="vawm-5bog wm-k"/><path class="esy3f6kir wm-k"/><path class="hy1ry4bey wm-shine"/><path class="rp_powb7f wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:star-half" /></template>
