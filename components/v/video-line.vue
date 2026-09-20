<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqyy_ubtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqyy_ubtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:video-line" /></template>
