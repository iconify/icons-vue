<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha7cf7b5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ha7cf7b5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:megaphone-fill-12" /></template>
