<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl21qac3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="vl21qac3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:translate-arabic-latin" /></template>
