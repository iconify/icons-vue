<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfyn1c49f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfyn1c49f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:oxygen" /></template>
