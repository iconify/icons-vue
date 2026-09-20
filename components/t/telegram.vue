<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s13fpy2sn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s13fpy2sn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:telegram" /></template>
