<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxw-xoi6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxw-xoi6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:task-fill" /></template>
