<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpt8t_sgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpt8t_sgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rudder-line" /></template>
