<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnafdbble.css';
import '../../css/i/in6vio3jf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nnafdbble"/><path class="in6vio3jf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:train-20" /></template>
