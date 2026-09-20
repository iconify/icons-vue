<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9-7nq4tg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9-7nq4tg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:tgt" /></template>
