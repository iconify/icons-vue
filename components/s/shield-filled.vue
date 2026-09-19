<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fobo14b-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fobo14b-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shield-filled" /></template>
