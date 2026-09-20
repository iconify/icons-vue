<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvdz56ifx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvdz56ifx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:storefront-minus-outline" /></template>
