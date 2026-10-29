<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cubi7abey.css';
import '../../css/x/x99v8ybav.css';
import '../../css/i/iz2h51hrs.css';
import '../../css/f/ffe6717hy.css';
import '../../css/l/lkq-umkya.css';
import '../../css/l/lvtq943uu.css';
import '../../css/l/lqlwayb9u.css';
import '../../css/m/mmyrs99pg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cubi7abey wm-shadow"/><path class="x99v8ybav"/><path class="iz2h51hrs"/><path class="ffe6717hy"/><path class="lkq-umkya"/><path class="lvtq943uu wm-shine"/><path class="lqlwayb9u"/><path class="mmyrs99pg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-plush:message-circle" /></template>
