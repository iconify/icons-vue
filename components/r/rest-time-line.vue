<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jowrko3lu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jowrko3lu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:rest-time-line" /></template>
