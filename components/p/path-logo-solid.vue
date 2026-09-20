<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6va4gs4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6va4gs4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:path-logo-solid" /></template>
