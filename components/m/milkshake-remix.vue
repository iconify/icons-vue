<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc-a7d1cl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kc-a7d1cl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:milkshake-remix" /></template>
