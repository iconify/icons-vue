<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn61-t-nk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bn61-t-nk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pocket" /></template>
