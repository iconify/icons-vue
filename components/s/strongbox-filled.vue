<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivmprj5xh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivmprj5xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:strongbox-filled" /></template>
