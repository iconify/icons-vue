<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2w5x-76v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b2w5x-76v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:vending-pack" /></template>
