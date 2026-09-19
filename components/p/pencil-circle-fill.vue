<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7ib8hdyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="w7ib8hdyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:pencil-circle-fill" /></template>
