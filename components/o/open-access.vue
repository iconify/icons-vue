<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otdmk9b3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":512};
const content = `<path class="otdmk9b3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:open-access" /></template>
