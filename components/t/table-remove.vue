<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uutp14pfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uutp14pfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table-remove" /></template>
