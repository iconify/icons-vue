<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vejl2qbsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vejl2qbsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:wise-logo" /></template>
