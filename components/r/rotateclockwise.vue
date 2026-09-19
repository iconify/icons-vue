<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejo68-63n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ejo68-63n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:rotateclockwise" /></template>
