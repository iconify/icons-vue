<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyrsg_bkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyrsg_bkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:store-mall-directory" /></template>
