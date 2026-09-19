<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/leex_ib_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="leex_ib_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:search" /></template>
