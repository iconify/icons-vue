<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7wn57bdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7wn57bdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:message-x-solid" /></template>
