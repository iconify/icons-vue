<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk-jk3b-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lk-jk3b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:sign-at" /></template>
