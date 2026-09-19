<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ma_0tgban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ma_0tgban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sine-wave-filled" /></template>
