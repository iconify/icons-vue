<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwt8ncc8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":488};
const content = `<path class="lwt8ncc8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:xing" /></template>
