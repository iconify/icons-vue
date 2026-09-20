<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkb5lwquw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zkb5lwquw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:triangles-centerline-dashed-vertical" /></template>
