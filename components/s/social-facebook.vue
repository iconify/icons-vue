<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdm0tqzzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sdm0tqzzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-facebook" /></template>
