<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ioza19b7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ioza19b7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-number-8-filled" /></template>
