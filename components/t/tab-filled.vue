<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kj8xb4akc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kj8xb4akc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tab-filled" /></template>
