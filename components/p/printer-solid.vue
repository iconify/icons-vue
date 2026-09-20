<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v29xqmoek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v29xqmoek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:printer-solid" /></template>
