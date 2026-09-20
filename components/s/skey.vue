<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-xjivbhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k-xjivbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:skey" /></template>
