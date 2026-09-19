<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr2-00fdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":29,"height":24};
const content = `<path class="sr2-00fdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:share-a" /></template>
