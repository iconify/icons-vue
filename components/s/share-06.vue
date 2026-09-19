<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbx2oobum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbx2oobum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:share-06" /></template>
