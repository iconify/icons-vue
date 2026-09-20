<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt50purwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nt50purwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:pen-solid" /></template>
