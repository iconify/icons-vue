<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_xpiwb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_xpiwb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-letter-k-filled" /></template>
