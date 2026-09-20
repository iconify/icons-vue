<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdzlb1bab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xdzlb1bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:test-tube-remix" /></template>
