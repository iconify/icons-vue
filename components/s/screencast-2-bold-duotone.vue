<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/baf92pb0v.css';
import '../../css/o/oxe30nuth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="baf92pb0v"/><path class="oxe30nuth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:screencast-2-bold-duotone" /></template>
