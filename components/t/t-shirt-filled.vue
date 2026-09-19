<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz_d1jkgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jz_d1jkgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:t-shirt-filled" /></template>
