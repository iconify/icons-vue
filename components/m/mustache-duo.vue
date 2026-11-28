<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prid3u2wn.css';
import '../../css/w/wcr5_ubdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prid3u2wn secondary"/><path class="primary wcr5_ubdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:mustache-duo" /></template>
