<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt9pubbnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wt9pubbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:network" /></template>
