<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfbp08bap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="sfbp08bap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:uni8d5e-box-filled" /></template>
