<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j791lm_cr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j791lm_cr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:map-signs" /></template>
