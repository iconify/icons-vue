<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b21udjbcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b21udjbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:radio-off" /></template>
