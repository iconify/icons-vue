<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dysvs-brd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dysvs-brd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:panel-top-filled" /></template>
