<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_qg1h19u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t_qg1h19u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:zoom-out-gesture-remix" /></template>
