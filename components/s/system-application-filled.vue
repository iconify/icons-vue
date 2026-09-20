<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz_r39ypr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hz_r39ypr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:system-application-filled" /></template>
