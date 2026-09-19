<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_b-gubjy.css';
import '../../css/m/m8pf_nbon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="x_b-gubjy"/><path class="m8pf_nbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:switch-button" /></template>
