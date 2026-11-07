<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0o9nrvdg.css';
import '../../css/m/mgns90b-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0o9nrvdg"/><path class="mgns90b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:question-mark-bold-duotone" /></template>
