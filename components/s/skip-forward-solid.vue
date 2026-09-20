<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-kth2bfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-kth2bfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:skip-forward-solid" /></template>
