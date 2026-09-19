<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2elzabfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="k2elzabfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:scale" /></template>
