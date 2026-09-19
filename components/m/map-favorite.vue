<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8-9vtl6c.css';
import '../../css/n/ng73f_8fh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="c8-9vtl6c"/><path class="ng73f_8fh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:map-favorite" /></template>
