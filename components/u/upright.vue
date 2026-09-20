<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh4gsqbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="dh4gsqbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:upright" /></template>
