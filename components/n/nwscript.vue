<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkrmi-1du.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tkrmi-1du"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:nwscript" /></template>
