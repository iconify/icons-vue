<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th_wgybyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="th_wgybyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:tower-filled" /></template>
