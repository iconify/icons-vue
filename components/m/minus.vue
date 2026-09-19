<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhy83-btp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":614};
const content = `<path class="uhy83-btp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:minus" /></template>
