<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq7_6ac2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jq7_6ac2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:stamp" /></template>
