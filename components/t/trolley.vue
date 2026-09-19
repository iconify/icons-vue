<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzf8ydn4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zzf8ydn4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:trolley" /></template>
