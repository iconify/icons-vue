<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snvlaybpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="snvlaybpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:pepper-hot" /></template>
