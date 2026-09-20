<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7hso62ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7hso62ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:meta-cafe-logo" /></template>
