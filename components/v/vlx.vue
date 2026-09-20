<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8f4kmatu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8f4kmatu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:vlx" /></template>
