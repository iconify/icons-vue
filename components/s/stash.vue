<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izvg8nb9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="izvg8nb9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:stash" /></template>
