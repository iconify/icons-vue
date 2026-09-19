<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6-zicbpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6-zicbpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:plane-land-filled" /></template>
