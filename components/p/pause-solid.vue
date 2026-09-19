<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htmdhfcry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htmdhfcry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:pause-solid" /></template>
