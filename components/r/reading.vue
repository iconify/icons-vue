<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zip20upao.css';
import '../../css/b/b4jm4y-yv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zip20upao"/><path class="b4jm4y-yv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:reading" /></template>
