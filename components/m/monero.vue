<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur-d651vm.css';
import '../../css/n/nzbz80bhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ur-d651vm"/><path class="nzbz80bhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:monero" /></template>
