<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_dkwcc0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_dkwcc0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:utya" /></template>
