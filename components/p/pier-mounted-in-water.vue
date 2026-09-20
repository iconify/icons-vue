<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3n8fp7oh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r3n8fp7oh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pier-mounted-in-water" /></template>
