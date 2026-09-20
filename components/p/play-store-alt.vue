<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo2-g_b4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path clip-rule="evenodd" class="oo2-g_b4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:play-store-alt" /></template>
