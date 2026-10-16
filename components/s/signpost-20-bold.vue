<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a60pyzb1b.css';
import '../../css/e/ejvwyfy7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a60pyzb1b"/><path class="ejvwyfy7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:signpost-20-bold" /></template>
