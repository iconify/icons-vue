<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywnaxmbog.css';
import '../../css/z/zaqxs8bvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywnaxmbog"/><path clip-rule="evenodd" class="zaqxs8bvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:meditation-bold" /></template>
