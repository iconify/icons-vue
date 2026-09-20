<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvbn4vepc.css';
import '../../css/k/kq37wbc8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvbn4vepc"/><path class="kq37wbc8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:paypal" /></template>
