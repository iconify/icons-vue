<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgcdr68to.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgcdr68to"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:toy-brick-minus" /></template>
