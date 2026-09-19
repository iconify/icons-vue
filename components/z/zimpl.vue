<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw___22ng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":476,"height":512};
const content = `<path class="qw___22ng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:zimpl" /></template>
