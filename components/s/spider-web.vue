<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmfv3actq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmfv3actq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:spider-web" /></template>
