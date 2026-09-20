<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk06r_61c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hk06r_61c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:map-marked-alt-solid" /></template>
