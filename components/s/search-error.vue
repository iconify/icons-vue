<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojl9vbc5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojl9vbc5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:search-error" /></template>
