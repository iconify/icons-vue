<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/caqrw6b9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="caqrw6b9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:square-root" /></template>
