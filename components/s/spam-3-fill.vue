<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usi-x5bch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usi-x5bch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:spam-3-fill" /></template>
