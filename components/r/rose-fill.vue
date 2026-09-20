<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilt_3uyjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilt_3uyjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rose-fill" /></template>
