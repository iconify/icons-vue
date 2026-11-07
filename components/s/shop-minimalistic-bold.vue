<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg0ekvbvc.css';
import '../../css/m/mkq5lkj0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg0ekvbvc"/><path class="mkq5lkj0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shop-minimalistic-bold" /></template>
