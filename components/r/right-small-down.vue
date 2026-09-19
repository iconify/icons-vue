<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5exhlb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x5exhlb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:right-small-down" /></template>
