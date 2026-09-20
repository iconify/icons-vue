<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qaapb3h_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qaapb3h_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:pac-man" /></template>
