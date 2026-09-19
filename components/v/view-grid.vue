<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4hv1ab-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="a4hv1ab-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:view-grid" /></template>
