<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z53litb-a.css';
import '../../css/b/bp0qj4bzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z53litb-a"/><path class="bp0qj4bzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:task" /></template>
