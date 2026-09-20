<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncoo9jbzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncoo9jbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:menu4-filled" /></template>
