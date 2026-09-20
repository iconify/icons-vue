<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wco_tabkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wco_tabkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pallete-2-outline" /></template>
