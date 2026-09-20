<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb6olcl2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="wb6olcl2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:text-desc" /></template>
