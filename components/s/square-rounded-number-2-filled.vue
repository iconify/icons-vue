<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz-s85hno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fz-s85hno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-number-2-filled" /></template>
