<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skeut9b6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skeut9b6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:octagon-fill" /></template>
