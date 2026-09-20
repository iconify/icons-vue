<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l76d3obsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l76d3obsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:password-pencil-solid" /></template>
