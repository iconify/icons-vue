<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njgul7b1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njgul7b1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:redo" /></template>
