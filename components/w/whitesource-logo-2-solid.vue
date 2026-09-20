<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw3z_lmzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yw3z_lmzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:whitesource-logo-2-solid" /></template>
