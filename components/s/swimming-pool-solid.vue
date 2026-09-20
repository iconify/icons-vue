<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmbsf60om.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jmbsf60om"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:swimming-pool-solid" /></template>
