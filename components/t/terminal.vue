<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa7zqbbpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xa7zqbbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:terminal" /></template>
