<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u85bfj4hg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="u85bfj4hg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:otter" /></template>
