<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7tkpmcfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d7tkpmcfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:user-secret" /></template>
