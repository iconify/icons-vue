<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzk20bw8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":770};
const content = `<path class="kzk20bw8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:panorama" /></template>
