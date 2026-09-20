<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zocpa-b9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zocpa-b9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-66-small" /></template>
