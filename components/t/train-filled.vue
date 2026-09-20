<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbhhsu2jg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbhhsu2jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:train-filled" /></template>
