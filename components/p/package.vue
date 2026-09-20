<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odj9mk72t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="odj9mk72t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:package" /></template>
