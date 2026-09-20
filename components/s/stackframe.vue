<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8v-2u13w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8v-2u13w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:stackframe" /></template>
