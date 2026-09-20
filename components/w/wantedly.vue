<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0z2e2bxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0z2e2bxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:wantedly" /></template>
