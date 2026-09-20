<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmlo9qblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmlo9qblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:rounded-corner" /></template>
