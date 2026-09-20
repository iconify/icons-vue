<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uak09kb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uak09kb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:storefront-edit" /></template>
