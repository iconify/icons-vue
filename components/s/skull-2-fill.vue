<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzd_86c9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzd_86c9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:skull-2-fill" /></template>
