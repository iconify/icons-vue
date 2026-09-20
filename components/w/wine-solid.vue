<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgy--9bou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sgy--9bou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:wine-solid" /></template>
