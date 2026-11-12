<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wotd8qb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wotd8qb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:quetre-light" /></template>
