<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfz3hpbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":432};
const content = `<path class="rfz3hpbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:repeat-one" /></template>
