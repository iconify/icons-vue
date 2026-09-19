<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rehko012o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rehko012o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:piggy-bank-filled" /></template>
