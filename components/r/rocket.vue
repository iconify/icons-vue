<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv29rccow.css';
import '../../css/y/yz7t0mb_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer iv29rccow"/><path class="duoicon-primary-layer yz7t0mb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:rocket" /></template>
