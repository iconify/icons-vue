<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o75vuubjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="o75vuubjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:play-small-outline" /></template>
