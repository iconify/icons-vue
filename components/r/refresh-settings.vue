<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjaqougjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="kjaqougjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:refresh-settings" /></template>
