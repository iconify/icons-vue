<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubmqqdb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ubmqqdb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:zip-outline" /></template>
