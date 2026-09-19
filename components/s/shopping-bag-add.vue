<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxgrj4bzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxgrj4bzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:shopping-bag-add" /></template>
