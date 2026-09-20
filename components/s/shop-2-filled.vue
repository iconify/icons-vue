<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kis6e-brh.css';
import '../../css/v/vefb5s21n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kis6e-brh"/><path class="vefb5s21n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:shop-2-filled" /></template>
