<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-61rbjll.css';
import '../../css/l/lo95uel6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<ellipse class="e-61rbjll"/><path class="lo95uel6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:sushi" /></template>
