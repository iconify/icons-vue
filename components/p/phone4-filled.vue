<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb5vreb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pb5vreb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:phone4-filled" /></template>
