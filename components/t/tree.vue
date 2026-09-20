<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-k8phbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="v-k8phbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:tree" /></template>
