<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvz9b_w7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jvz9b_w7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:medialyze" /></template>
