<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng6blccig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ng6blccig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:person-crop-circle-badge-checkmark" /></template>
