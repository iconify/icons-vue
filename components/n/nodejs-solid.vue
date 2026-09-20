<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlk9qlb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="mlk9qlb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:nodejs-solid" /></template>
