<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtoqlkbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="rtoqlkbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:shuffle-arrows-filled" /></template>
