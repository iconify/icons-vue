<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_yi9saap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n_yi9saap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:skip-forward-solid" /></template>
