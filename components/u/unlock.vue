<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv7ibq-3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="bv7ibq-3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:unlock" /></template>
