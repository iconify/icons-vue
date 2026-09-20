<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qf8ooobpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qf8ooobpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:virus-antivirus-solid" /></template>
