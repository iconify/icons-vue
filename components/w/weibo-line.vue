<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lex7ucbrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lex7ucbrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:weibo-line" /></template>
