<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lizqbob8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lizqbob8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:vip-fill" /></template>
