<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcc876b3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dcc876b3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:ruler-solid" /></template>
