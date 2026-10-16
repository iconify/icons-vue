<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rey63kbbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="rey63kbbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:openfeature-light" /></template>
