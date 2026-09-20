<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht17a1bxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ht17a1bxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:move-up-left" /></template>
