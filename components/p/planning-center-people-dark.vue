<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4ed8ob3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v4ed8ob3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:planning-center-people-dark" /></template>
