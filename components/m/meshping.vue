<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjjhel9ot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sjjhel9ot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:meshping" /></template>
