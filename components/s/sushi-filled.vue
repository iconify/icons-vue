<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unkwe7bpp.css';
import '../../css/u/uqzyn-kgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unkwe7bpp"/><path class="uqzyn-kgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sushi-filled" /></template>
