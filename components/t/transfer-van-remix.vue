<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2ragxbas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="b2ragxbas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:transfer-van-remix" /></template>
