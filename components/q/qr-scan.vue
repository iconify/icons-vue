<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvaaipbio.css';
import '../../css/v/v6qkiubvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvaaipbio"/><path class="v6qkiubvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:qr-scan" /></template>
