<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w80iqw.css';
import '../../css/s/so-from-60.css';
import '../../css/f/fill-to-1.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w80iqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:security-filled" /></template>
