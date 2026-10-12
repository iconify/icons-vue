<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3jzqsvjd.css';
import '../../css/o/o1j_wmpcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f3jzqsvjd"/><path class="o1j_wmpcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:ticket-stroke-20" /></template>
