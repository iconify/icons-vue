<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn8awebqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tn8awebqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:snowy-line" /></template>
