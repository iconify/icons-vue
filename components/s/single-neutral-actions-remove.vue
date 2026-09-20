<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3lstkfqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3lstkfqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:single-neutral-actions-remove" /></template>
