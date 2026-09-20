<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaf725b_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uaf725b_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimalistic-magnifer-bug-outline" /></template>
