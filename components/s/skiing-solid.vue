<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm2nhjbdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qm2nhjbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:skiing-solid" /></template>
