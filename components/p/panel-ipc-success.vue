<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkqd1b__q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="nkqd1b__q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:panel-ipc-success" /></template>
