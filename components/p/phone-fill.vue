<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0j186b5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c0j186b5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:phone-fill" /></template>
