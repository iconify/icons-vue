<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpdvekbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kpdvekbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rewind-10-seconds-forward-outline" /></template>
