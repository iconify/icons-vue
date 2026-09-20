<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxtkoeb2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="oxtkoeb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:one-one-one" /></template>
