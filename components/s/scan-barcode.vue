<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ches-xu_a.css';
import '../../css/r/rv1mylbja.css';
import '../../css/x/x9xwxpbju.css';
import '../../css/s/smwjpcb8b.css';
import '../../css/z/zhcigbb2u.css';
import '../../css/j/j4ih1tbdo.css';
import '../../css/n/ngclmx6fg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ches-xu_a wm-shadow"/><path class="rv1mylbja wm-k"/><path class="wm-k x9xwxpbju"/><path class="smwjpcb8b wm-a"/><path class="wm-a zhcigbb2u"/><path class="j4ih1tbdo wm-a"/><path class="ngclmx6fg wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:scan-barcode" /></template>
