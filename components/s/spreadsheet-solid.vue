<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfq8lxbqj.css';
import '../../css/k/k24wn5bei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hfq8lxbqj"/><path clip-rule="evenodd" class="k24wn5bei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:spreadsheet-solid" /></template>
