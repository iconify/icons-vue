<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5i_igbuz.css';
import '../../css/l/ldw2udbvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5i_igbuz"/><path class="ldw2udbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:share-forward" /></template>
