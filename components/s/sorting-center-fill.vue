<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7joa7pmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l7joa7pmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sorting-center-fill" /></template>
