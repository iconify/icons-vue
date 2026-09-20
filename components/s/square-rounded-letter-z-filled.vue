<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxxcrkbgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxxcrkbgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-letter-z-filled" /></template>
