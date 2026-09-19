<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnuadmb2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="gnuadmb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:otfeature-ss03-small-filled" /></template>
