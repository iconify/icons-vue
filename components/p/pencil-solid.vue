<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjbvsf14a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjbvsf14a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:pencil-solid" /></template>
