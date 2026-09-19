<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oke2ykbej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="oke2ykbej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:pencil-stroke-12" /></template>
