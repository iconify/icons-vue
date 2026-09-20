<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6g4jnb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t6g4jnb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:virustotal-logo-solid" /></template>
