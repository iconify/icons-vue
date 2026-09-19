<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw6s-92eq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":898,"height":1024};
const content = `<path class="qw6s-92eq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:thermometeralt" /></template>
