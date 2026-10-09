<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-4x9ob7y.css';
import '../../css/t/t47nc4b6q.css';
import '../../css/a/amdspubws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d-4x9ob7y"/><path class="t47nc4b6q"/><path class="amdspubws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:van-20-bold" /></template>
