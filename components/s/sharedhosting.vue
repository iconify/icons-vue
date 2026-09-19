<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-16e2k1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="g-16e2k1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:sharedhosting" /></template>
