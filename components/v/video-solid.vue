<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x99brs7fk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x99brs7fk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:video-solid" /></template>
