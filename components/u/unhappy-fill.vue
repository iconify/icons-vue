<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j71x9tmmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j71x9tmmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:unhappy-fill" /></template>
