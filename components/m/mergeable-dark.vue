<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8p_-6bjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w8p_-6bjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mergeable-dark" /></template>
