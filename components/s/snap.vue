<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b67w6_c5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="b67w6_c5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:snap" /></template>
