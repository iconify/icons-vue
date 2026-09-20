<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hccwo5byp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hccwo5byp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:skull-2-solid" /></template>
