<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oywa71ble.css';
import '../../css/v/vf-xpzeqo.css';
import '../../css/k/ko9sw4b7p.css';
import '../../css/t/tnrvi8b7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oywa71ble"/><path class="vf-xpzeqo"/><path class="ko9sw4b7p"/><path class="tnrvi8b7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:yaw-20" /></template>
