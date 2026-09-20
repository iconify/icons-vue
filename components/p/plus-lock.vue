<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkw2z3lzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkw2z3lzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:plus-lock" /></template>
