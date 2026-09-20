<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb0bh0b5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rb0bh0b5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:shield-solid" /></template>
