<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgavx_zmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pgavx_zmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:share-link-remix" /></template>
