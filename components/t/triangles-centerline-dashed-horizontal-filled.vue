<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oquz9_65a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oquz9_65a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:triangles-centerline-dashed-horizontal-filled" /></template>
