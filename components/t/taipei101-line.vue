<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcn44kbbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcn44kbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:taipei101-line" /></template>
