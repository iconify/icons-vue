<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-6qnccdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-6qnccdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:medium-logo-3" /></template>
