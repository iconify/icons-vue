<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl8db2yaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tl8db2yaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:signa" /></template>
