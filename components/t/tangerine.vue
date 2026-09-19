<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9ow01geo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="g9ow01geo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:tangerine" /></template>
