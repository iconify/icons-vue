<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp_u8u75x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wp_u8u75x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:shopping-bag-solid" /></template>
