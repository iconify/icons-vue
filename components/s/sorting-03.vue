<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue64i0bvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ue64i0bvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:sorting-03" /></template>
