<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqrfxzblb.css';
import '../../css/e/e5nrzwjsg.css';
import '../../css/f/fh8bft_rz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fqrfxzblb"/><path class="e5nrzwjsg"/><path class="fh8bft_rz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mirror-20-bold" /></template>
