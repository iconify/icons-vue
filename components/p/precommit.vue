<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvb27_qwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mvb27_qwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:precommit" /></template>
