<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb8e2pbvs.css';
import '../../css/a/a6q6jbntf.css';
import '../../css/a/avibf5j5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qb8e2pbvs"/><path class="a6q6jbntf"/><path class="avibf5j5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:vite" /></template>
