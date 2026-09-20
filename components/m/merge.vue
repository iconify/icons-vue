<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qef9l7bhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="qef9l7bhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:merge" /></template>
