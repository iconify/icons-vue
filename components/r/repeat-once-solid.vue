<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4ikh4a_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4ikh4a_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:repeat-once-solid" /></template>
