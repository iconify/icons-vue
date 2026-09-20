<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5a99hb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a5a99hb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:reply-2-linear" /></template>
