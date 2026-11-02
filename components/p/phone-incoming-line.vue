<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_4-tccpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_4-tccpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:phone-incoming-line" /></template>
