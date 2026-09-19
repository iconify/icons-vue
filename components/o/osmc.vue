<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kos593b4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kos593b4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:osmc" /></template>
