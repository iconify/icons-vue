<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec1c9ybub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ec1c9ybub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:mood-confuzed-filled" /></template>
