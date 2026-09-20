<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fapr92-oh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fapr92-oh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:velocity" /></template>
