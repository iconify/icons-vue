<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl_3dwbej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl_3dwbej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:protein" /></template>
