<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oahu7obbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oahu7obbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:rainbow-off" /></template>
