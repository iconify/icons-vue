<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2vh7sqhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e2vh7sqhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:mubi-logo-solid" /></template>
