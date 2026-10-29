<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gnhf0cczt.css';
import '../../css/u/uzb644j9v.css';
import '../../css/t/tyl_u5bcc.css';
import '../../css/y/y9gz_6bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="gnhf0cczt"/><path class="uzb644j9v wm-a"/><path class="tyl_u5bcc wm-a"/><path class="y9gz_6bcp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:popcorn-duo" /></template>
