<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1sxc4bzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r1sxc4bzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:test-react" /></template>
