<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghlx8ic-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ghlx8ic-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:srlty" /></template>
