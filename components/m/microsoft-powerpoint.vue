<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyyt5hbdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nyyt5hbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:microsoft-powerpoint" /></template>
