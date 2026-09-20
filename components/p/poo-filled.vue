<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zflz6tblo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zflz6tblo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:poo-filled" /></template>
