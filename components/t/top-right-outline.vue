<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylee5g30h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ylee5g30h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:top-right-outline" /></template>
