<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyh-60p9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kyh-60p9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:object-group" /></template>
