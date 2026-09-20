<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qli8pklap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qli8pklap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:pump" /></template>
