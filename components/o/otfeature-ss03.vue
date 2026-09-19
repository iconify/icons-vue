<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gst0b_6kn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="gst0b_6kn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:otfeature-ss03" /></template>
