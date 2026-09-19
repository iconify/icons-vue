<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0m8oyg9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t0m8oyg9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:stop-sharp" /></template>
