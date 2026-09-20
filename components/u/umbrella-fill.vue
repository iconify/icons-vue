<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrg5sccwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrg5sccwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:umbrella-fill" /></template>
