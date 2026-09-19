<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9--45bfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9--45bfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:phone" /></template>
