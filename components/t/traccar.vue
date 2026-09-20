<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln0duzf9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ln0duzf9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:traccar" /></template>
