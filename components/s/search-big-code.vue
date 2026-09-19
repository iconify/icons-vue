<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd6gj6bbb.css';
import '../../css/i/ifptogbbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pd6gj6bbb"/><path class="ifptogbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:search-big-code" /></template>
