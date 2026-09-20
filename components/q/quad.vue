<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyyga3pdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kyyga3pdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:quad" /></template>
