<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otvodrc4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otvodrc4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sofa-solid" /></template>
