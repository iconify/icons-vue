<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f19zj7btg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f19zj7btg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:users-round-collaboration" /></template>
