<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv7o_0b3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dv7o_0b3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ribbon-health" /></template>
