<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbou95b_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbou95b_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:rotate-left-filled" /></template>
