<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8qo-qb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u8qo-qb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:z-wave-logo-solid" /></template>
