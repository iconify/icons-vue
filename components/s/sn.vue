<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-cpdlxtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-cpdlxtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:sn" /></template>
