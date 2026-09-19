<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk99sab7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fk99sab7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:taxi" /></template>
