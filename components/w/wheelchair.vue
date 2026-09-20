<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpfk69-0z.css';
import '../../css/f/fnee-c65g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="rpfk69-0z"/><path class="fnee-c65g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:wheelchair" /></template>
