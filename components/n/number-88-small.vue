<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwj0sbclr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwj0sbclr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-88-small" /></template>
