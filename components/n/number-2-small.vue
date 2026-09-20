<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkvyznc6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkvyznc6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-2-small" /></template>
