<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkaai1b1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dkaai1b1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sunrise" /></template>
