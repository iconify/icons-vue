<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx27k-jtf.css';
import '../../css/n/ngwmr6pgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wx27k-jtf"/><path class="ngwmr6pgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ttk" /></template>
