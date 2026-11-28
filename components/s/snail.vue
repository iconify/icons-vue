<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3xfm5bgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3xfm5bgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:snail" /></template>
