<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcd09qz-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcd09qz-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:times-circle-solid" /></template>
