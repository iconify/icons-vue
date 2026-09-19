<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q919pubya.css';
import '../../css/e/epbp3tnvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="q919pubya"/><path class="epbp3tnvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:pin-fill" /></template>
