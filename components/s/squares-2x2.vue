<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdgkpzv5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zdgkpzv5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:squares-2x2" /></template>
