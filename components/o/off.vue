<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akhwoit6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":660,"height":717};
const content = `<path class="akhwoit6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:off" /></template>
