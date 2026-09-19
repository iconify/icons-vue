<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gveut4b0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":640};
const content = `<path class="gveut4b0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:projector" /></template>
