<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im8enibwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="im8enibwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:settings-1-fill" /></template>
