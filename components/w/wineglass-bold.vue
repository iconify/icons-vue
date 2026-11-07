<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucsituugr.css';
import '../../css/n/nfab9gbzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucsituugr"/><path class="nfab9gbzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wineglass-bold" /></template>
