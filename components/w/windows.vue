<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hknn8vb1a.css';
import '../../css/k/ko05ptbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hknn8vb1a"/><path class="ko05ptbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:windows" /></template>
