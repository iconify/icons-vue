<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2el319gf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v2el319gf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:spacing-large-16" /></template>
