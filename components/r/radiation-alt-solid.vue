<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mco1f--7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mco1f--7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:radiation-alt-solid" /></template>
