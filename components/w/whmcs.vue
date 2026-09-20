<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo_8dnbfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yo_8dnbfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:whmcs" /></template>
