<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d64-tcb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":400,"height":488};
const content = `<path class="d64-tcb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:scribd" /></template>
