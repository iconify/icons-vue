<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpgjb18la.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpgjb18la"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:nuxt" /></template>
