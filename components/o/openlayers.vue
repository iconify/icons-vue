<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt5086bag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bt5086bag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:openlayers" /></template>
