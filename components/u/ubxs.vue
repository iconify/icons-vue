<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ladlm4_ju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ladlm4_ju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ubxs" /></template>
