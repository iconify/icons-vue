<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzcrhv3ky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jzcrhv3ky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:mug-hot" /></template>
