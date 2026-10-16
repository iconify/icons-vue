<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm68y3b7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":800,"height":800};
const content = `<path class="gm68y3b7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:notary-project-dark" /></template>
