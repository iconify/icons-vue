<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq2n5dunw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lq2n5dunw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-radical-thin" /></template>
