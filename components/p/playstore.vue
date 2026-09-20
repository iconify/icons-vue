<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm4a30b9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="zm4a30b9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:playstore" /></template>
