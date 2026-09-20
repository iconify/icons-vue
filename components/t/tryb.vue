<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkqqq9htt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dkqqq9htt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:tryb" /></template>
