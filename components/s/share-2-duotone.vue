<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prq4-o15b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prq4-o15b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:share-2-duotone" /></template>
