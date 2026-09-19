<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irzz9_mlb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":1024};
const content = `<path class="irzz9_mlb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pivotx" /></template>
