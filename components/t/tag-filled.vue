<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdhrm5bky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdhrm5bky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tag-filled" /></template>
