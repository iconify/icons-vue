<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et29cpbnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="et29cpbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:reactive-resume-dark" /></template>
