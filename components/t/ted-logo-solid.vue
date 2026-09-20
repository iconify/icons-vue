<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw2xxxbob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xw2xxxbob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:ted-logo-solid" /></template>
