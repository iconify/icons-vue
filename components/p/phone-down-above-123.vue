<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2w8fkt6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="w2w8fkt6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:phone-down-above-123" /></template>
