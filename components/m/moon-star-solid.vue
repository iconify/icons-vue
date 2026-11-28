<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i43f51ivn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i43f51ivn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:moon-star-solid" /></template>
