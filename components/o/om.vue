<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmzpugqmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bmzpugqmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:om" /></template>
