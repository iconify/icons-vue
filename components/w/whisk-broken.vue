<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz7vl2bem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xz7vl2bem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:whisk-broken" /></template>
