<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z86z4ciyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z86z4ciyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:search-plus" /></template>
