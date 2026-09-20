<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9xm-gbea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n9xm-gbea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:viber" /></template>
