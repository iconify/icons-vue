<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkvkkpbvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkvkkpbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:reset-left-fill" /></template>
