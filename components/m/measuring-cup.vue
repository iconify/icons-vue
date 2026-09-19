<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a07m1ch5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a07m1ch5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:measuring-cup" /></template>
