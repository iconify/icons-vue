<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rr28mrwkz.css';
import '../../css/h/hna37so3u.css';
import '../../css/s/su958tz7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rr28mrwkz"/><path class="hna37so3u"/><path class="su958tz7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tea-cup-48-bold" /></template>
