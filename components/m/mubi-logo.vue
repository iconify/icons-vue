<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2u1_lkgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2u1_lkgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:mubi-logo" /></template>
