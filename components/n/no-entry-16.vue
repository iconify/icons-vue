<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xptn6ibfq.css';
import '../../css/v/voqlvbrhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xptn6ibfq"/><path class="voqlvbrhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:no-entry-16" /></template>
