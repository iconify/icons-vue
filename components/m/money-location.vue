<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vazhz5-2p.css';
import '../../css/a/auct0ubxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="vazhz5-2p"/><path class="auct0ubxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:money-location" /></template>
