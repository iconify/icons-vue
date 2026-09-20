<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7-sbloho.css';
import '../../css/l/lfpx5tcva.css';
import '../../css/s/s3btd85nz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7-sbloho"/><path class="lfpx5tcva"/><path class="s3btd85nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:people-carry" /></template>
