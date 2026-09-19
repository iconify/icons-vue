<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr_un4bow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sr_un4bow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:polymer" /></template>
