<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t68yh9beu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t68yh9beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:nest-wifi-logo-solid" /></template>
