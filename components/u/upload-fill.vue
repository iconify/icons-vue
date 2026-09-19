<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk1ieab_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rk1ieab_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:upload-fill" /></template>
