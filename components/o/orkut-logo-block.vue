<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2g0k_bbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u2g0k_bbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:orkut-logo-block" /></template>
