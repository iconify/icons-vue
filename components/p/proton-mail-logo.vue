<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3h3j67jh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3h3j67jh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:proton-mail-logo" /></template>
