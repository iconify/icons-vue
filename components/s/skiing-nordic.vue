<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkz0r345s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="kkz0r345s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:skiing-nordic" /></template>
