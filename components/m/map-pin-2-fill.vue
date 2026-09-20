<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt6fpzbdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tt6fpzbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:map-pin-2-fill" /></template>
