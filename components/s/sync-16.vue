<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krsjxac7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="krsjxac7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:sync-16" /></template>
