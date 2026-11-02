<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odt1v8bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odt1v8bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:share-3-fill" /></template>
