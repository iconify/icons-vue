<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm6_lzbpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="fm6_lzbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:truck" /></template>
