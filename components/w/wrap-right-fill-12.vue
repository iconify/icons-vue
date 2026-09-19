<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_ses9b1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="t_ses9b1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:wrap-right-fill-12" /></template>
