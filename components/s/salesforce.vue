<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fib_oobro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fib_oobro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:salesforce" /></template>
