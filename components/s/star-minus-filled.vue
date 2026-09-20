<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy9jcwcfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uy9jcwcfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:star-minus-filled" /></template>
