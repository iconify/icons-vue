<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v891yolpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v891yolpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:user-20" /></template>
