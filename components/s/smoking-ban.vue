<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9ymmxkfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j9ymmxkfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:smoking-ban" /></template>
