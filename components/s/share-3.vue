<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oas4cbcex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oas4cbcex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:share-3" /></template>
