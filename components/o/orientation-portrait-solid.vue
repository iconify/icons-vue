<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-dv1svnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d-dv1svnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:orientation-portrait-solid" /></template>
