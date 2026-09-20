<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smn_1ccdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="smn_1ccdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:share-link-remix" /></template>
