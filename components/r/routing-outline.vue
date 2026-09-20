<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0ohg_b9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s0ohg_b9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:routing-outline" /></template>
