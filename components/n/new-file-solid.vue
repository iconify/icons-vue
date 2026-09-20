<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm86fibta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nm86fibta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:new-file-solid" /></template>
