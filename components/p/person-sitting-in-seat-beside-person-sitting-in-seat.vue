<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sld4zn5wc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sld4zn5wc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-sitting-in-seat-beside-person-sitting-in-seat" /></template>
