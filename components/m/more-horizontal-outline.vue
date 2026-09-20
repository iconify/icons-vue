<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-nldbc4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y-nldbc4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:more-horizontal-outline" /></template>
