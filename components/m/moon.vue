<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u00i3huun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u00i3huun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:moon" /></template>
