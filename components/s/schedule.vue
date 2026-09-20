<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-64w7biu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-64w7biu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:schedule" /></template>
