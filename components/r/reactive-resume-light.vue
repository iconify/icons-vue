<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkleqj0hc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vkleqj0hc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:reactive-resume-light" /></template>
