<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esjgdibig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="esjgdibig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:pod" /></template>
