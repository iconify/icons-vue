<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km1ccqbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="km1ccqbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:patch-fixes-outlined" /></template>
