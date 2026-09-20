<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8toi509j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r8toi509j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:thumbsdown-16" /></template>
