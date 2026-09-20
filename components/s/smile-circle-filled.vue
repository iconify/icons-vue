<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxpkqfi6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xxpkqfi6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:smile-circle-filled" /></template>
