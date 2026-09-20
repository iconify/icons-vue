<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eoj8bc9hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eoj8bc9hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:smug-mug-logo-block" /></template>
