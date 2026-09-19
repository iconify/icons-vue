<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz44xsv-i.css';
import '../../css/i/i6iu0p2uk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bz44xsv-i"/><path class="i6iu0p2uk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-bookmarks" /></template>
