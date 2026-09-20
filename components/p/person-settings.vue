<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bafd-0bfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bafd-0bfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:person-settings" /></template>
