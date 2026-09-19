<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbhnw7wcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbhnw7wcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:mobile-back-alt-filled" /></template>
