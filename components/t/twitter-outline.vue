<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/valmru-ia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="valmru-ia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:twitter-outline" /></template>
