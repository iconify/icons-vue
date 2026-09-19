<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf6ew-d1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf6ew-d1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:tado" /></template>
