<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-gl1e30s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":961,"height":1024};
const content = `<path class="k-gl1e30s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:yiiframework" /></template>
