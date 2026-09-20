<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv4eu2o7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vv4eu2o7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:unfold-more-fill" /></template>
