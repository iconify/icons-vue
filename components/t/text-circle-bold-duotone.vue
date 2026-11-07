<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrdvcwidb.css';
import '../../css/d/d-g40esoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrdvcwidb"/><path class="d-g40esoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-circle-bold-duotone" /></template>
