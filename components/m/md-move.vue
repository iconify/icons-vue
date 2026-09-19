<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/viava94rx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="viava94rx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-move" /></template>
