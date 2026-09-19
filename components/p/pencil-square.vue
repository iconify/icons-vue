<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnixj-hrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="lnixj-hrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:pencil-square" /></template>
