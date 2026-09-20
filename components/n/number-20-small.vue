<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxwq0k3ap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxwq0k3ap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-20-small" /></template>
