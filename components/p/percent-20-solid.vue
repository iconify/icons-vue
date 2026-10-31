<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxu9710-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wxu9710-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:percent-20-solid" /></template>
