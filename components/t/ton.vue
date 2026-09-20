<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/loq-8obfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="loq-8obfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ton" /></template>
