<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2ds8_m2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q2ds8_m2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:shopping-basket-off-filled" /></template>
