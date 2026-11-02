<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohx7zzbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohx7zzbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:right-small-fill" /></template>
