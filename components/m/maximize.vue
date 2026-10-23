<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cddph3buh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cddph3buh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:maximize" /></template>
