<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae_emfbaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ae_emfbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:positive-24px" /></template>
