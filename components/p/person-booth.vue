<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5kp83b8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="k5kp83b8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:person-booth" /></template>
