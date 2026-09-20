<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf82ihf2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="rf82ihf2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:mood-sad-solid" /></template>
