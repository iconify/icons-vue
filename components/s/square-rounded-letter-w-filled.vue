<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjd2aeb2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjd2aeb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-letter-w-filled" /></template>
