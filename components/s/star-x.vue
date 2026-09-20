<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnb5tybzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lnb5tybzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:star-x" /></template>
