<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yipof0bqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="yipof0bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:npm-solid" /></template>
