<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_82q38za.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":25,"left":4};
const content = `<path class="s_82q38za"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:radix-ui-light" /></template>
