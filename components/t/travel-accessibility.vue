<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr32yxbru.css';
import '../../css/a/aa4zmqbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hr32yxbru"/><path clip-rule="evenodd" class="aa4zmqbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:travel-accessibility" /></template>
