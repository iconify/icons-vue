<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb-ml4nyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nb-ml4nyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:tree-catalog-filled" /></template>
