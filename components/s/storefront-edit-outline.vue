<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0x9hmbyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0x9hmbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:storefront-edit-outline" /></template>
