<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwg0nbcog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xwg0nbcog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:shopping-trolley" /></template>
