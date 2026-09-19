<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1y1v-t3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1y1v-t3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:triangle-02" /></template>
