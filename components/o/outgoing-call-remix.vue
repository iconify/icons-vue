<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdb3783_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cdb3783_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:outgoing-call-remix" /></template>
