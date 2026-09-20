<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f91v1qb7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f91v1qb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:typography-16" /></template>
