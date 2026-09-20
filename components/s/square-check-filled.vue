<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzx7ebb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzx7ebb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-check-filled" /></template>
