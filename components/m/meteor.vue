<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jikhc-6ib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jikhc-6ib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:meteor" /></template>
