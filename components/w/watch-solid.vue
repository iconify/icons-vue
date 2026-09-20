<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udqx-wbgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udqx-wbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:watch-solid" /></template>
