<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grh95ibtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="grh95ibtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:reward-stars-4-bold" /></template>
