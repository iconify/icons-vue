<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5g88-oui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5g88-oui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sun-fill" /></template>
