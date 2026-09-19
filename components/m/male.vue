<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhw-b4bcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1023};
const content = `<path class="qhw-b4bcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:male" /></template>
