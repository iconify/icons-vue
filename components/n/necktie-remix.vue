<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbzyrs_fn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cbzyrs_fn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:necktie-remix" /></template>
