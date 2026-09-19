<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh1_soi9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vh1_soi9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:shoulder" /></template>
