<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/j0ghh_c0v.css';
import '../../css/m/ml0wobb6r.css';
import '../../css/t/tygsh6hqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="j0ghh_c0v"/><path class="ml0wobb6r wm-shadow"/><path class="tygsh6hqg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:plane-engrave" /></template>
