<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyj5a3q_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gyj5a3q_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:separator-vertical" /></template>
