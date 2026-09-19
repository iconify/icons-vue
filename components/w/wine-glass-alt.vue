<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5rmaob2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":288,"height":512};
const content = `<path class="k5rmaob2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:wine-glass-alt" /></template>
