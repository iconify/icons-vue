<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtai9hb3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtai9hb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:scissors-solid" /></template>
