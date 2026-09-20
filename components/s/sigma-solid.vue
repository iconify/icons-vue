<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2jfj-b6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e2jfj-b6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:sigma-solid" /></template>
