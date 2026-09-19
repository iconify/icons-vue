<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apsjy4boa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="apsjy4boa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:volume-off-sharp" /></template>
