<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs5bxsbdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="zs5bxsbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:user-sync" /></template>
