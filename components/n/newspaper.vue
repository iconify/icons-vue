<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh8alabfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="eh8alabfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:newspaper" /></template>
