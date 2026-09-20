<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8y5xackw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="c8y5xackw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:section-remove-solid" /></template>
