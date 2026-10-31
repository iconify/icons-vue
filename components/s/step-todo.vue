<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kez3htb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="kez3htb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="struq:step-todo" /></template>
