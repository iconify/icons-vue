<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv5gi5b9f.css';
import '../../css/l/l624pqxrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zv5gi5b9f"/><path class="l624pqxrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:uranium-20-bold" /></template>
