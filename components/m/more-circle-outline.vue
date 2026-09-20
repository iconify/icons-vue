<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od72l_b0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="od72l_b0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:more-circle-outline" /></template>
