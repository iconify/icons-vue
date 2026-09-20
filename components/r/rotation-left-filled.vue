<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uottdfb7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uottdfb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:rotation-left-filled" /></template>
