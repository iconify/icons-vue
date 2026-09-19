<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-vd53b8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="c-vd53b8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:teamviewer" /></template>
