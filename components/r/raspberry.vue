<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbr5cdchm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1025};
const content = `<path class="pbr5cdchm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:raspberry" /></template>
