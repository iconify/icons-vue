<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljvk73k3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljvk73k3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:sort" /></template>
