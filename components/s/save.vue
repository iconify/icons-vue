<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm33n6bfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tm33n6bfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:save" /></template>
