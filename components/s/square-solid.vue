<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l--fddcds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l--fddcds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:square-solid" /></template>
