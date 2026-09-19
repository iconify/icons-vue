<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ul4ei0bva.css';
import '../../css/l/lwmq8uo7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ul4ei0bva"/><path class="lwmq8uo7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:mobile-alt" /></template>
