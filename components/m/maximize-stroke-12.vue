<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl4ijetfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="nl4ijetfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:maximize-stroke-12" /></template>
