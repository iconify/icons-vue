<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rul21fapv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rul21fapv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:minus-expressive" /></template>
