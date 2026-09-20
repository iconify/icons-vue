<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpp7dkhsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpp7dkhsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:paste-fill" /></template>
