<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a779bccpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a779bccpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:zoom-out" /></template>
