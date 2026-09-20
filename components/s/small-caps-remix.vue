<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kijblibvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kijblibvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:small-caps-remix" /></template>
