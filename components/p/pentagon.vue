<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev65m7dkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ev65m7dkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:pentagon" /></template>
