<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbc7sbboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbc7sbboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-letter-s-filled" /></template>
