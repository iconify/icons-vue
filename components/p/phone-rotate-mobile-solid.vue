<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li1w34b2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="li1w34b2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:phone-rotate-mobile-solid" /></template>
