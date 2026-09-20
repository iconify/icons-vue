<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6-j7ubto.css';
import '../../css/n/njy7e9b_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="v6-j7ubto"/><path class="njy7e9b_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openuem-light" /></template>
