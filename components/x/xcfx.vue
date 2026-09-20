<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_441roht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s_441roht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:xcfx" /></template>
