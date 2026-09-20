<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptr56cnqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptr56cnqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:soundcloud" /></template>
