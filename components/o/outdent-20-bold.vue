<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cww23ibou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cww23ibou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:outdent-20-bold" /></template>
