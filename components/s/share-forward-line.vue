<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7o570b7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n7o570b7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:share-forward-line" /></template>
