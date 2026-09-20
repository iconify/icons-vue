<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa6oe_bbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xa6oe_bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:one-finger-short-tap-solid" /></template>
