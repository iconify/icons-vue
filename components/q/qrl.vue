<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agas_nbbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agas_nbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:qrl" /></template>
