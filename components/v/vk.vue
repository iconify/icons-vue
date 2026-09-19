<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8fafzncn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x8fafzncn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:vk" /></template>
