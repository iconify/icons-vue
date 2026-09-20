<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx5z0ablq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rx5z0ablq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:three-dogs-under-dog-sled" /></template>
