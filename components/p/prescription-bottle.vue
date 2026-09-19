<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfqsajb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="qfqsajb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:prescription-bottle" /></template>
