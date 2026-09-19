<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1s7dnb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1s7dnb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:menu-search-filled" /></template>
