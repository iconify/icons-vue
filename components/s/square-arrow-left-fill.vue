<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/boi4y04jk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="boi4y04jk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:square-arrow-left-fill" /></template>
