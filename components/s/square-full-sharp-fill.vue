<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxh7ddskd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dxh7ddskd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-full-sharp-fill" /></template>
