<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu9lgye8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xu9lgye8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pin-pad-with-euro" /></template>
