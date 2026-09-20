<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyu2l48ig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eyu2l48ig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:paypal-logo-block" /></template>
