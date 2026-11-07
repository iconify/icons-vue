<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzprmcg0c.css';
import '../../css/o/otqm0acos.css';
import '../../css/o/oaa-h-w6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzprmcg0c"/><path class="otqm0acos"/><path class="oaa-h-w6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:move-vertical-bold-duotone" /></template>
