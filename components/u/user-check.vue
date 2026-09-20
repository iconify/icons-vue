<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5wero0ri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5wero0ri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:user-check" /></template>
