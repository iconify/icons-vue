<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9uac9b_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="k9uac9b_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:transgender" /></template>
