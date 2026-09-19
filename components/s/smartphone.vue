<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw82yk4cu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tw82yk4cu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:smartphone" /></template>
