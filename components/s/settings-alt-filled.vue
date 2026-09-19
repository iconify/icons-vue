<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imw6l2u6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imw6l2u6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:settings-alt-filled" /></template>
