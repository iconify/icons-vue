<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia6lvkaoj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ia6lvkaoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:status" /></template>
