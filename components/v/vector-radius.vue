<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzk_pozbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzk_pozbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vector-radius" /></template>
