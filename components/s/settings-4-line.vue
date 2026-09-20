<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_lh51auu.css';
import '../../css/n/nmf1tu78z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_lh51auu"/><path class="nmf1tu78z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:settings-4-line" /></template>
