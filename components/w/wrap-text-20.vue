<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eic0a8bvd.css';
import '../../css/g/g1il7ubyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="eic0a8bvd"/><path class="g1il7ubyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wrap-text-20" /></template>
