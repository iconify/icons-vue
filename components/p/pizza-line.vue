<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8nqnqjtu.css';
import '../../css/h/hgrdrccsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8nqnqjtu"/><path class="hgrdrccsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pizza-line" /></template>
