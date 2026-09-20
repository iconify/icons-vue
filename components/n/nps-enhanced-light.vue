<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukk_oybpm.css';
import '../../css/u/u-7z_t4fb.css';
import '../../css/v/v-q4e7xtu.css';
import '../../css/j/ju0jd-e1r.css';
import '../../css/u/us33y-a5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ukk_oybpm"/><path class="u-7z_t4fb"/><path class="v-q4e7xtu"/><path class="ju0jd-e1r"/><path class="us33y-a5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nps-enhanced-light" /></template>
