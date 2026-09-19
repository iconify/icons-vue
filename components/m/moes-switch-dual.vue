<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k49k42c2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k49k42c2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:moes-switch-dual" /></template>
