<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sde3gc6on.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sde3gc6on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:undertake-hold-up-filled" /></template>
