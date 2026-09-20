<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqm37pb8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fqm37pb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:star-circle-outline" /></template>
