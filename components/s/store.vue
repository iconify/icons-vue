<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6e28u54x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6e28u54x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:store" /></template>
