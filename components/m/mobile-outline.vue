<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqp2ybc7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bqp2ybc7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:mobile-outline" /></template>
