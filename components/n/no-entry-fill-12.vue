<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2jbinb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="u2jbinb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:no-entry-fill-12" /></template>
