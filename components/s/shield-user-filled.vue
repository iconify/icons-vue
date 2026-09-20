<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd4eude7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hd4eude7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:shield-user-filled" /></template>
