<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a599-h6nt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a599-h6nt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:open-umbrella-solid" /></template>
