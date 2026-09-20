<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro9gsfbig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ro9gsfbig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:vending-machine-with-greek-cross" /></template>
