<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izsch6fso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izsch6fso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:male-solid" /></template>
