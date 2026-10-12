<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d759uxleu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d759uxleu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:ship-cargo-filled" /></template>
