<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnw29gb3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gnw29gb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:volume-level-high-solid" /></template>
