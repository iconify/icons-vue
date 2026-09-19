<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pl3x99q7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pl3x99q7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:remove-sharp" /></template>
