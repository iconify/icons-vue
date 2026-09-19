<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggqxp-m1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggqxp-m1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:store-filled" /></template>
