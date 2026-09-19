<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivz9d7brs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ivz9d7brs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:sort" /></template>
