<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgl7dnbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgl7dnbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:undo-right-broken" /></template>
