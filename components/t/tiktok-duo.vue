<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hy1r4hwit.css';
import '../../css/b/bkd0k5o0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hy1r4hwit secondary"/><path class="bkd0k5o0y primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tiktok-duo" /></template>
