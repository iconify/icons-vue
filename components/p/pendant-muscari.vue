<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afn6kfbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afn6kfbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:pendant-muscari" /></template>
