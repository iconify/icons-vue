<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt31z2vjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qt31z2vjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:multiple-forward-left-outline" /></template>
