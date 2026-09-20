<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnhl-5bip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tnhl-5bip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:radio" /></template>
