<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/koz_5vb4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="koz_5vb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:table-rows-split-filled" /></template>
