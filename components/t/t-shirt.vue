<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhmd9mu1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bhmd9mu1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:t-shirt" /></template>
