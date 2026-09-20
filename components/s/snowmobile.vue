<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x26ijbb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="x26ijbb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:snowmobile" /></template>
