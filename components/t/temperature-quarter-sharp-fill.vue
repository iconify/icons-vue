<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1powsbeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1powsbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:temperature-quarter-sharp-fill" /></template>
