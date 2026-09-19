<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcmscowbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcmscowbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:shopping-cart" /></template>
