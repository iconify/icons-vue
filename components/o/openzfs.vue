<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je73ojbch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="je73ojbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openzfs" /></template>
