<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssc66acas.css';
import '../../css/a/a4x15ccoa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ssc66acas"/><path class="a4x15ccoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rewind-5-seconds-forward-bold" /></template>
