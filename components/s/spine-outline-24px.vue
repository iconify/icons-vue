<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5_bh3bds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n5_bh3bds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:spine-outline-24px" /></template>
