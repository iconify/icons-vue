<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swzw7xbys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swzw7xbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:text-uppercase" /></template>
