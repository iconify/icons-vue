<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0e1_pbyx.css';
import '../../css/a/a7x3g_3uk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0e1_pbyx"/><path clip-rule="evenodd" class="a7x3g_3uk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:masks-bold" /></template>
