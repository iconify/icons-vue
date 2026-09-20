<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cak87qbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cak87qbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:test-tube-empty" /></template>
