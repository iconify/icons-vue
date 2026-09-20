<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs17gcz1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qs17gcz1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ycc" /></template>
