<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a85qzclsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a85qzclsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:moon-16" /></template>
