<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0t_852bq.css';
import '../../css/l/lihbolbto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0t_852bq"/><circle class="lihbolbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:shopping-tag" /></template>
