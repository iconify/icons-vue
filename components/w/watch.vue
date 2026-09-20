<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xb2uscbun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xb2uscbun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:watch" /></template>
