<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pl2egfq-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pl2egfq-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:taxi" /></template>
