<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-phwvw3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="e-phwvw3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:mobile-phone-11" /></template>
