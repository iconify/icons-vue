<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shjpjzbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="shjpjzbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:objective-j" /></template>
