<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz-7qynvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rz-7qynvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:next-outline" /></template>
