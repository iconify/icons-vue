<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx8_flw1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lx8_flw1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pixellance" /></template>
