<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q35sru-em.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="q35sru-em"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:schedule-outlined" /></template>
