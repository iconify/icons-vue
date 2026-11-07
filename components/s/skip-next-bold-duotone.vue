<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr5sybb7w.css';
import '../../css/c/cdhe4sbui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cr5sybb7w"/><path class="cdhe4sbui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:skip-next-bold-duotone" /></template>
