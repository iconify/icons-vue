<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kskna-bmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kskna-bmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:mail-send-envelope-remix" /></template>
