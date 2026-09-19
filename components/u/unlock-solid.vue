<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv3y6zk0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="hv3y6zk0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:unlock-solid" /></template>
