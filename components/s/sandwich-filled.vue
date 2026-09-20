<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7ihd2b_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7ihd2b_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:sandwich-filled" /></template>
