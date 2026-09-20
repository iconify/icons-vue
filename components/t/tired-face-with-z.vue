<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-v_u_7lw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t-v_u_7lw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tired-face-with-z" /></template>
