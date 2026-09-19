<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-iie2b0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="k-iie2b0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:mergecells" /></template>
