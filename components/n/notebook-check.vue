<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2mplmbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2mplmbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:notebook-check" /></template>
