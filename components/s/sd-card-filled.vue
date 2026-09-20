<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4mc388uz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y4mc388uz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sd-card-filled" /></template>
