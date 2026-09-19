<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rirdx665u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="rirdx665u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:phalcon" /></template>
