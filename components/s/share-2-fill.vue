<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7sd8bcqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d7sd8bcqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:share-2-fill" /></template>
