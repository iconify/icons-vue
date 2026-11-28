<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg8f99aak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dg8f99aak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:ship" /></template>
