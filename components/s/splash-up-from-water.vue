<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t53n6nbft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t53n6nbft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:splash-up-from-water" /></template>
