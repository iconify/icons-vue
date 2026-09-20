<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht78eobpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ht78eobpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:nodebb" /></template>
