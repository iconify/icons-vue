<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdhn607fe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tdhn607fe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:x-p-ferd-light" /></template>
