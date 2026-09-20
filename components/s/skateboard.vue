<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spg4x5bvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="spg4x5bvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:skateboard" /></template>
