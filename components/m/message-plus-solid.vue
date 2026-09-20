<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzdx2iy2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="mzdx2iy2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:message-plus-solid" /></template>
