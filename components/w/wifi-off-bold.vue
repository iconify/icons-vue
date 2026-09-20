<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgnn-dbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgnn-dbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:wifi-off-bold" /></template>
