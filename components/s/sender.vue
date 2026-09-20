<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3x-gpp8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k3x-gpp8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:sender" /></template>
