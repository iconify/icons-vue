<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b08gyib0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b08gyib0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:shield-x-solid" /></template>
