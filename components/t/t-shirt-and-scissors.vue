<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcqte1bgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bcqte1bgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:t-shirt-and-scissors" /></template>
