<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by-tp_ohk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="by-tp_ohk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:power-off-fill" /></template>
