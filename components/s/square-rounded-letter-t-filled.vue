<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8961_5of.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8961_5of"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-letter-t-filled" /></template>
