<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjgy0_bnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjgy0_bnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:queue-list-solid" /></template>
