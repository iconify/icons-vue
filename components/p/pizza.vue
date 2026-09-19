<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skglo3xlk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="skglo3xlk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pizza" /></template>
