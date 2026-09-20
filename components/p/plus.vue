<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn85zbh0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":16};
const content = `<path class="fn85zbh0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:plus" /></template>
