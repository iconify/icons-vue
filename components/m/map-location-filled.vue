<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3i8uzbyg.css';
import '../../css/e/edwthhmnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="q3i8uzbyg"/><path class="edwthhmnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:map-location-filled" /></template>
