<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp_83_ara.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lp_83_ara"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:message-minus-solid" /></template>
