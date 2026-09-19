<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2osepb0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="n2osepb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:round-pushpin-filled" /></template>
