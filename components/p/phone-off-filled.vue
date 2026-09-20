<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfq_mub-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfq_mub-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:phone-off-filled" /></template>
