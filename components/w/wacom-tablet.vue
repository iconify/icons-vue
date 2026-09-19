<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypjqnzb2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":17};
const content = `<path class="ypjqnzb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:wacom-tablet" /></template>
