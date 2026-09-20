<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8d7nab0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8d7nab0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:shop-fill" /></template>
