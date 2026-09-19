<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj1ehrbwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="hj1ehrbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:translate-cyrillic-latin" /></template>
