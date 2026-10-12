<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa7izibxv.css';
import '../../css/t/t9gs7gpae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qa7izibxv"/><path clip-rule="evenodd" class="t9gs7gpae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:train-front-tunnel-filled" /></template>
