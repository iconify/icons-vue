<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v496_6y4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v496_6y4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:yuan-yen-remix" /></template>
