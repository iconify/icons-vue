<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnoc0t9do.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnoc0t9do"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:seat-legroom-extra" /></template>
