<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4p7r1b0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u4p7r1b0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-minus-circle-fill" /></template>
