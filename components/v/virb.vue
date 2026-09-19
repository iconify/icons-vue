<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj4pa9fcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":448};
const content = `<path class="oj4pa9fcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:virb" /></template>
