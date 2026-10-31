<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djvu6_z9o.css';
import '../../css/w/wxfft0bkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="djvu6_z9o"/><path class="wxfft0bkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:palau" /></template>
