<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lor2r5p4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lor2r5p4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:multiple-neutral-2" /></template>
