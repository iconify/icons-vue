<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly7e9mbbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ly7e9mbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:shopping-basket-2-line" /></template>
