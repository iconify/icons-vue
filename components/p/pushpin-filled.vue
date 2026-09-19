<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghu6qbdwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ghu6qbdwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:pushpin-filled" /></template>
