<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9dxnnbae.css';
import '../../css/s/spzrtb9gd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x9dxnnbae"/><path class="spzrtb9gd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:shuffle-sharp" /></template>
