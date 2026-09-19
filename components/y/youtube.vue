<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mprhoobup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":14};
const content = `<path class="mprhoobup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:youtube" /></template>
