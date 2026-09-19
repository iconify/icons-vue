<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8lcblbrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k8lcblbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-times-fill" /></template>
