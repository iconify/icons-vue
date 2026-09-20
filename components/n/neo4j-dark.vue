<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8zaambxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i8zaambxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:neo4j-dark" /></template>
