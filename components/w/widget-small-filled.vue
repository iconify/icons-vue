<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1t66kn2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1t66kn2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:widget-small-filled" /></template>
