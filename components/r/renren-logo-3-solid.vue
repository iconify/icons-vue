<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2nudd3_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a2nudd3_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:renren-logo-3-solid" /></template>
