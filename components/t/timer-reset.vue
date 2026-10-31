<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/y/y_yc9pjvn.css';
import '../../css/i/iod2rc--u.css';
import '../../css/r/ru_m_q-rd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="wm-shadow y_yc9pjvn"/><path class="iod2rc--u wm-shadow"/><path class="ru_m_q-rd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:timer-reset" /></template>
