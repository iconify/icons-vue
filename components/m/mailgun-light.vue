<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/touqn-bdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="touqn-bdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mailgun-light" /></template>
