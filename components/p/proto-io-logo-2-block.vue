<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuachbc_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kuachbc_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:proto-io-logo-2-block" /></template>
