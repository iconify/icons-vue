<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pecu2cc1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pecu2cc1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-top-bold" /></template>
