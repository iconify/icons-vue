<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbnphpbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tbnphpbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-percent-fill" /></template>
