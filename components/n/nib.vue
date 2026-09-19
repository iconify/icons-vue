<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfav-9bvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gfav-9bvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:nib" /></template>
