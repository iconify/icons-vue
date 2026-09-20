<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8c1tdb3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f8c1tdb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:reorder-bold" /></template>
