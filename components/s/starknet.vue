<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxz2cui4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oxz2cui4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:starknet" /></template>
