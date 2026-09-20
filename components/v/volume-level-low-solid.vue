<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdr8b69no.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xdr8b69no"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:volume-level-low-solid" /></template>
