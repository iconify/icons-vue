<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss6rcc_ua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ss6rcc_ua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:password-alt-filled" /></template>
