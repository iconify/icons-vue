<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmde_brvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmde_brvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:speaking" /></template>
