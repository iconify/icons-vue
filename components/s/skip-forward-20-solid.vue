<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl9a3_bxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="fl9a3_bxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:skip-forward-20-solid" /></template>
