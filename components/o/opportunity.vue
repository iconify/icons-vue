<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjhi-eznz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pjhi-eznz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:opportunity" /></template>
