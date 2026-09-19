<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwnttcb1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":758,"height":614};
const content = `<path class="xwnttcb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:minus" /></template>
