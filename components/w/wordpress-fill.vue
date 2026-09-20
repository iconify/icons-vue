<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzyl80b9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="yzyl80b9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:wordpress-fill" /></template>
