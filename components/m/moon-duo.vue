<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgzmasisn.css';
import '../../css/x/xycz9duzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary sgzmasisn"/><path class="primary xycz9duzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:moon-duo" /></template>
