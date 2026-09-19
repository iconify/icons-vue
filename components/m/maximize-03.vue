<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqfn3tbyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqfn3tbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:maximize-03" /></template>
