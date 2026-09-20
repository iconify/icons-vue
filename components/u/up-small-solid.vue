<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6aot1rla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="w6aot1rla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:up-small-solid" /></template>
