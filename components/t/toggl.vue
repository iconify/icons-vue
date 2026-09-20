<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt_7kd49m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vt_7kd49m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:toggl" /></template>
