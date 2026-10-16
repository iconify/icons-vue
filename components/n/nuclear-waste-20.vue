<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzgrz9d2f.css';
import '../../css/l/llp7d6wph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hzgrz9d2f"/><path class="llp7d6wph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:nuclear-waste-20" /></template>
