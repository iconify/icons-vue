<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fwjzuebfl.css';
import '../../css/b/bbwt9j4jc.css';
import '../../css/i/iqe7qjbhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="fwjzuebfl"/><path class="bbwt9j4jc"/><path class="iqe7qjbhy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:onion" /></template>
