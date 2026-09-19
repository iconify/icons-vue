<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xk88s11pw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xk88s11pw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:subscriptions-created" /></template>
