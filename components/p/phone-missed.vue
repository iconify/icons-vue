<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rolv1m5rx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rolv1m5rx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:phone-missed" /></template>
