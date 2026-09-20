<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/buu_4mbhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="buu_4mbhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rose-line" /></template>
