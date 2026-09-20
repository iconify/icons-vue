<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k53k_dblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k53k_dblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:move-duotone" /></template>
