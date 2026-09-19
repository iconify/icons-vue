<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts0-w2bzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ts0-w2bzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-minus-thin" /></template>
