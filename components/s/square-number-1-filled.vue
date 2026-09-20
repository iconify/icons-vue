<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkup8_7we.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkup8_7we"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-number-1-filled" /></template>
