<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p65_h2bqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p65_h2bqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:medium-logo-3-solid" /></template>
