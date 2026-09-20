<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnhjd7j_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="hnhjd7j_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:package-filled" /></template>
