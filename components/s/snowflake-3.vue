<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aix1bbbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="aix1bbbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:snowflake-3" /></template>
