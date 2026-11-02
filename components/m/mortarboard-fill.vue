<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hihomp6hz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hihomp6hz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mortarboard-fill" /></template>
