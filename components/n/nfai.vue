<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oho6lgbrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oho6lgbrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:nfai" /></template>
