<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2g07ihhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r2g07ihhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:meta-logo-bold" /></template>
