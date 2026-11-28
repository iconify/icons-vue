<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/paykg7zgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="paykg7zgg primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:swimmer-duotone" /></template>
