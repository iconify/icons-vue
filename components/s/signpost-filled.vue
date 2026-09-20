<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po87r3bol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="po87r3bol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:signpost-filled" /></template>
