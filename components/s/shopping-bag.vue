<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu2b1hbwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vu2b1hbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:shopping-bag" /></template>
