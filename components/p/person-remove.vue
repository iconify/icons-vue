<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-21c-j5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e-21c-j5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:person-remove" /></template>
