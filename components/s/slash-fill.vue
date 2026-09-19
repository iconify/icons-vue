<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1h05ubxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1h05ubxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:slash-fill" /></template>
